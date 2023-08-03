+++
title = "ApproxMCv3: A modern approximate model counter"
date = 2018-11-25T11:06:17+05:30
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mate Soos"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++

<p>ApproxMC is a scalable, approximate model counter that provides PAC (probably approximately correct) guarantees. We have been working very hard on speeding up approximate model counting for SAT and have made real progress. The research paper, accepted at AAAI-19 is available <a href="https://www.cs.toronto.edu/~meel/Papers/aaai19-sm.pdf">here</a>. The code is available <a href="https://github.com/meelgroup/ApproxMC">here</a> (release with static binary <a href="https://github.com/meelgroup/ApproxMC/releases">here</a>). The main result is that we can solve a <strong>lot</strong> more problems than before. The speed of solving is orders(!) of magnitude faster than the previous best system:</p>
<p><img class="size-full wp-image-3214 aligncenter" src="http://www.msoos.org/wordpress/wp-content/uploads/2018/11/Screenshot_20181125_202611.png" alt="" width="1202" height="740" srcset="https://www.msoos.org/wordpress/wp-content/uploads/2018/11/Screenshot_20181125_202611.png 1202w, https://www.msoos.org/wordpress/wp-content/uploads/2018/11/Screenshot_20181125_202611-300x185.png 300w, https://www.msoos.org/wordpress/wp-content/uploads/2018/11/Screenshot_20181125_202611-768x473.png 768w, https://www.msoos.org/wordpress/wp-content/uploads/2018/11/Screenshot_20181125_202611-1024x630.png 1024w" sizes="(max-width: 1202px) 100vw, 1202px" /></p>
<h3>Background</h3>
<p>The idea of approximate model counting, originally <a href="https://arxiv.org/pdf/1306.5726">by Chakraborty, Meel and Vardi</a> was a huge hit back in 2013, and many papers have followed it, trying to improve its results. All of them were basically tied to <a href="https://github.com/msoos/cryptominisat">CryptoMiniSat</a>, the SAT solver that is maintained by Mate, as all of them relied on XOR constraints being added to the regular CNF of a typical SAT problem.</p>
<p>So it made sense to examine what CryptoMiniSat could do to improve the speed of approximate counting. This time interestingly coincided with the removal of XORs in CryptoMiniSat. The problem was the following: A lot of new in- and preprocessing systems were being invented, mostly by Armin Biere et al, and they couldn't be added to CryptoMiniSat, because they didn&#8217;t take into account XOR constraints. They handled CNF just fine, but not XORs. So XORs became a burden, and they were removed in versions 3 and 4 of CryptoMiniSat. But there was need, and this being an exciting area, the XORs had to come back.</p>
<h3>Blast-Inprocess-Recover-Destroy</h3>
<p>But how to both have and not have XOR constraints? Re-inventing all the algorithms for XORs was not a viable option. The solution we came up with was a rather trivial one: forget the XORs during inprocessing and recover them after. The CNF would always remain the source of truth. Extracting all the XORs after in- and preprocessing would allow us to run the Gauss-Jordan elimination on the XORs post-recovery.</p>
<p>The process is conceptually quite easy:</p>
<ol>
<li><strong>Blast</strong> all XORs into clauses that are in the input using intermediate variables.</li>
<li><strong>Perform</strong> <strong>pre- or inprocessing</strong>.</li>
<li><strong>Recover the XORs</strong> from the CNF.</li>
<li><strong>Run the CDCL and Gauss-Jordan</strong> code at the same time.</li>
<li><strong>Destroy the XORs</strong> and goto 2.</li>
</ol>
<p>This system allows for everything to be in CNF form, lifting the XORs out when necessary and then forgetting them when it&#8217;s convenient. All of these steps are rather trivial, except <b>recovery</b>, as explained below.</p>
<h3>XOR recovery</h3>
<p>Recovering XORs sounds like a trivial task. Let&#8217;s say we have the following clauses</p>

<pre class="wp-block-preformatted">
 x1 V  x2 V  x3
-x1 V -x2 V  x3
 x1 V -x2 V -x3
-x1 V  x2 V -x3
</pre>

<p>This is conceptually equivalent to the XOR v1+v2+v3=1. So recovering this is trivial, and has been done before, by Heule in particular, in his <a href="http://www.st.ewi.tudelft.nl/sat/theses/heule_phd.pdf">PhD thesis</a>. The issue with the above is the following: a stronger system than the above still implies the XOR, but doesn&#8217;t look the same. For example:</p>

<pre class="wp-block-preformatted">
 x1 V  x2 V  x3
-x1 V -x2 V  x3
 x1 V -x2 V -x3
-x1 V  x2
</pre>

<p>This is almost equivalent to the previous set of clauses, but misses a literal from one of the clauses. It still implies the XOR of course. Now what? And what to do when missing literals mean that an entire clause can be missing? The algorithm to recover XORs in such cases is non-trivial. It&#8217;s non-trivial not only because of the complexity of how many combinations of missing literals and clauses there can be (it&#8217;s exponential) but because one must do this work extremely fast because SAT solvers are sensitive to time.</p>
<p>The algorithm that is in the <a href="https://www.cs.toronto.edu/~meel/Papers/aaai19-sm.pdf">paper</a> explains all the bit-fiddling and cache-friendly data layout used along with some fun algorithms. We even managed to use compiler intrinsics to use target-specific assembly instructions for hamming weight calculation.</p>
<h3>The results</h3>
<p>The results, as shown above, speak for themselves. Problems that took thousands of seconds to solve can now be solved under 20. The reason for such incredible speedup is basically the following: CryptoMiniSatv2 was way too clunky and didn&#8217;t have all the fun stuff that CryptoMiniSatv5 has, plus the XOR handling was incorrect, loosing XORs and the like. The published algorithm solves the underlying issue and allows CNF pre- and inprocessing to happen independent of XORs, thus enabling CryptoMiniSatv5 to be used in all its glory. And CryptoMiniSatv5 is <em>fast,</em> as per the this year&#8217;s SAT Competition <a href="http://sat2018.forsyte.tuwien.ac.at/index.php?cat=results">results</a>.</p>

<p><i>We thank the <a href="https://www.nscc.sg/">National Supercomputing Center Singapore</a>  that allowed us to run a large number of benchmarks on their machines, using at least 200 thousand CPU hours to make this paper. </i>This post has been adapted from <a href="https://www.msoos.org/2018/11/approxmcv3-a-modern-approximate-model-counter/">Mate's post</a> on ApproxMCv3.</p>
