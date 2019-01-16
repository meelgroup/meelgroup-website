+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "News"
subtitle = ""

# Order that this section will appear in.
weight = 30

# Number of publications to list.
count = 4

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
list_format = 2

+++
<!--- 
News item template. Copy all lines between # and paste.
#

            <span class="date text-muted">20 June 2018</span>
            <p>I will be at IJCAI from July 12 – July 19 and at Leiden University on
July 20. I will be co-presenting <a href="http://www.comp.nus.edu.sg/~meel/Tutorials/ijcai18.html">tutorial</a> with Supratik Chakraborty at
IJCAI on July 13.</p>


#
--> 
<div id="news" class="container-fluid">
<ul class="news list-unstyled">
<li class="shortnews">

<span class="date text-muted">6 December 2019</span>
            <p> Our paper on interpretable classification rules is accepted for publication at AIES 2019. Congratulations Bishwa on his first paper during PhD! Authors: Bishwamittra Ghosh  and Kuldeep S. Meel  </p>

            <span class="date text-muted">30 November 2018</span>
            <p>The next version of ApproxMC is here: <a href="https://github.com/meelgroup/approxmc">ApproxMC3</a> is faster and better than ever before. Do read <a href="https://www.msoos.org/2018/11/approxmcv3-a-modern-approximate-model-counter/">Mate’s post</a> for quick synopsys of the magic sauce behind ApproxMC’s performance.  </p>
            <span class="date text-muted">30 November 2018</span>
            <p>Congratulations Alexis for a successful defense of Masters thesis </p>
<span class="date text-muted">04 Novemeber 2018</span><p>
Kuldeep was awarded Distinguished Program Committee Member for <a href="https://www.ijcai-18.org/distinguished-members/"> IJCAI 2018</a>.</p>
<span class="date text-muted">01 Novemeber 2018</span><p>3 Papers accepted at AAAI-19!<br \> The first paper describes a new architecture for CNF-XOR formulas, which has allowed us to have a new approximate counter that is at least 100 times faster than ApproxMC2 – credit to <a href=http://www.msoos.org> Mate Soos  </a> for his breakthrough engineering that enabled this project!<br \> The second paper proposes the first algorithmic framework to test the distribution of a sampler.We show that several samplers output distributions far from what they claim!<br \>
The third paper shows that several relaxations of probabilsitic inference do not give any computational advantage, raising concerns about the motivations behind their usage.</p>
<span class="date text-muted">24 September 2018</span>
            <p> Our paper on uniform sampling based on knowledge compilation is accepted at LPAR-22. Authors: Shubham Sharma, Rahul Gupta, Subhajit Roy, and Kuldeep S. Meel  </p>



     
</li>

</ul>
</div>
