+++
title = "Bosphorus: An ANF and CNF simplifier and converter"
date = 2019-01-05T11:06:17+05:30
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
We are happy to release our ANF and CNF simplifier and converter called <a href="https://github.com/meelgroup/bosphorus">Bosphorus</a>. It has helped us break multiple real-world ciphers. It has been re-released with major work by Davin Choo & Kian Ming A. Chai from <a href="https://www.dso.org.sg/">DSO National Laboratories</a> Singapore and Mate Soos & Kuldeep Meel from NUS. The <a href="https://www.comp.nus.edu.sg/~meel/Papers/date-cscm19.pdf">paper</a> will be published at the <a href="https://www.date-conference.com/">DATE 2019</a> conference.



<h3>ANFs and CNFs</h3>



Algebraic Normal Form is a form that is used by most cryptographers to describe symmetric ciphers, hash algorithms, and lately a lot of <a href="https://csrc.nist.gov/projects/post-quantum-cryptography">post-quantum asymmetric ciphers</a>. It&#8217;s a very simple notation that basically looks like this: 



<pre class="wp-block-preformatted">x1 ⊕ x2 ⊕ x3 = 0<br>x1 * x2 ⊕ x2 * x3 + 1 = 0</pre>



Where &#8220;⊕&#8221; represents XOR and &#8220;*&#8221; represents the AND operator. So the first line here is an XOR of binary variables x1, x2 and x3 and their XOR must be equal to 0. The second line means that &#8220;(x1 AND x2)  XOR (x2 AND x3)&#8221; must be equal to 1. This normal form allows to see a bunch of interesting things. For example, it allows us to see the so-called &#8220;maximum degree&#8221; of the set of equations, where the degree is the maximum number of variables AND-ed together in one line. The above set of equations has a maximum degree of 2, as (x1*x2) is of degree 2. Degrees can often be a good indicator for the complexity of a problem.



What&#8217;s good about ANFs is that there are a number of well-known algorithms to break problems described in them. For example, one can do <a href="https://link.springer.com/content/pdf/10.1007%2F3-540-48405-1_2.pdf">(re)linearization</a> and Gauss-Jordan elimination, or one could run Grobner-basis algorithms such as <a href="https://en.wikipedia.org/wiki/Faug%C3%A8re%27s_F4_and_F5_algorithms">F4/F5</a> on it. Sometimes, the ANFs can also be solved by converting them to another normal form, Conjunctive Normal Form (CNF), used by SAT solvers. The CNF normal form looks like:



<pre class="wp-block-preformatted">x1 V x2 V x3<br>-x1 V x3</pre>



Where x1, x2 and x3 are binary variables, &#8220;V&#8221; is the logical OR, and each line must be equal to TRUE. Using CNF is interesting, because the solvers used to solve them, <a href="https://en.wikipedia.org/wiki/Boolean_satisfiability_problem">SAT solvers</a>, typically provide a different set of trade-offs for solving than ANF problem solvers. SAT solvers tend to use more CPU time but a lot less memory, sometimes making problems viable to solve in the &#8220;real world&#8221;. Whereas sometimes breaking of a cipher is enough to be demonstrated on paper, it also happens that one wants to break a cipher in the <a href="https://twitter.com/David3141593/status/1080606827384131590">real world</a>.



<h3>Bridging and Simplifying</h3>



We believe that Bosphorus is a first of its kind system that allows ANFs to be simplified using both CNF- and ANF-based systems. It can also convert between the two normal forms and can act both as an ANF and a CNF preprocessor, like <a href="http://fmv.jku.at/papers/EenBiere-SAT05.pdf">SatELite</a> (by Een and Biere) was for CNF. We believe this makes Bosphorus unique and also uniquely useful, especially while working on ANFs.



Bosphorus uses an iterative architecture that performs the following set of steps, either until it runs out of time or until fixed point:



<ol><li>Replace variables and propagate constants in the ANF </li><li>Run limited <a href="https://en.wikipedia.org/wiki/XSL_attack">Extended Linarization (XL)</a>  and inject back unit and binary XORs</li><li>Run limited <a href="https://rd.springer.com/content/pdf/10.1007%2F978-3-642-34047-5_18.pdf">ElimLin</a>  and inject back unit and binary XORs</li><li>Convert to CNF, run a SAT solver for a limited number of conflicts and inject back unit and binary (and potentially longer) XORs</li></ol>

![alt_text](Bosphorus.png)

In other words, the system is an iterative simplifier/preprocessor that invokes multiple reasoning systems to try to simplify the problem as much as possible. It can outright solve the system, as most of these reasoning systems are complete, but the point is to run them only to a certain limit and inject back into the ANF the easily &#8220;digestible&#8221; information. The simplified ANF can then either be output as an ANF or a CNF.



Bosphorus can also take a CNF as input, perform the trivial transformation of it to ANF and then treat it as an ANF. This allows the CNF to be simplified using techniques previously unavailable to CNF systems, such as XL.



<h3>ANF to CNF Conversion</h3>



ANF-to-CNF conversion is not considered that hard, and that&#8217;s why there hasn&#8217;t been too much academic effort devoted to it. However, it&#8217;s an important step without which a lot of opportunities would be missed.



The implemented system contains a pretty advanced ANF-to-CNF converter, using Karnaugh tables through <a href="https://en.wikipedia.org/wiki/Espresso_heuristic_logic_minimizer">Espresso</a>, XOR cutting, monomial reuse, etc. It should give a pretty optimal CNF for all ANFs. So Bosphorus can be used also just as an ANF-to-CNF converter, though it&#8217;s so much more.



<h3>Final Thoughts</h3>



One of the biggest capabilities of <a href="https://github.com/meelgroup/bosphorus">Bosphorus</a> is that it can simplify/preprocess ANF systems so more heavyweight ANF solvers can have a go at them. Its ANF simplification is so powerful, it can even help to solve some CNFs by lifting them to ANF, running the ANF simplifiers, converting it back to CNF, and solving that(!). We believe our initial results, published in the <a href="https://www.comp.nus.edu.sg/~meel/Papers/date-cscm19.pdf">paper</a>, are very encouraging. Further, the system is in a ready-to-use state: there is a <a href="https://cloud.docker.com/repository/docker/msoos/bosphorus">Docker image</a>, the source should build without a hitch, and there is even a precompiled Linux <a href="https://github.com/meelgroup/bosphorus/releases/">binary</a>. We would love to hear about your experience using it.

<i>Thanks to Karsten Nohl from <a href="https://srlabs.de/">Security Research Labs.</a></i> This post has been adapted from <a href="https://www.msoos.org/2019/01/bosphorus-an-anf-and-cnf-simplifier-and-converter/">Mate's post</a> on Bosphorus.
