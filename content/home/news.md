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
<span class="date text-muted">04 Novemeber 2018</span><p>
Kuldeep was awarded Distinguished Program Committee Member for <a href="https://www.ijcai-18.org/distinguished-members/"> IJCAI 2018</a>.</p>
<span class="date text-muted">01 Novemeber 2018</span><p>3 Papers accepted at AAAI-19!<br \> The first paper describes a new architecture for CNF-XOR formulas, which has allowed us to have a new approximate counter that is at least 100 times faster than ApproxMC2 – credit to <a href=http://www.msoos.org> Mate Soos  </a> for his breakthrough engineering that enabled this project!<br \> The second paper proposes the first algorithmic framework to test the distribution of a sampler.We show that several samplers output distributions far from what they claim!<br \>
The third paper shows that several relaxations of probabilsitic inference do not give any computational advantage, raising concerns about the motivations behind their usage.</p>
<span class="date text-muted">24 September 2018</span>
            <p> Our paper on uniform sampling based on knowledge compilation is accepted at LPAR-22. Authors: Shubham Sharma, Rahul Gupta, Subhajit Roy, and Kuldeep S. Meel  </p>
           <span class="date text-muted">29 August 2018</span>
            <p>Kuldeep's PhD thesis was awarded Honorable mention for ACP (Association of Constraint Programming) Doctoral Dissertation award at its annual conference CP 2018. </p>

            <span class="date text-muted">12 August 2018</span>
            <p>We will be presenting three papers at CP 2018. The first talk on network reliability is on Monday 27th Aug while the second talk on <a href="https://www.comp.nus.edu.sg/~meel/Papers/CP2018msv.pdf"> FPRAS for DNF</a> is on Wed, 29th Aug. The third talk on interpretable classification rules is on Thursday, 30th Aug. </p>

       


            <span class="date text-muted">8 August 2018</span>
            <p>Kuldeep Meel has been appointed <a href="http://giving.nus.edu.sg/prof-s/#sung_kah_kay">Sung Kah Kay Assistant Professor</a> </p>

     



            <span class="date text-muted">30 July 2018</span>
            <p> <a href="http://home.iitk.ac.in/~bhavish/"> Bhavishya</a> finished a successful summer internship and will be returning to IIT Kanpur for his third year. </p>





            <span class="date text-muted">23 July 2018</span>
            <p>Yash Pote has joined as a Research assistant. Welcome Yash! </p>
</li>

</ul>
</div>
