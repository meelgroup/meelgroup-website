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
weight = 40

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


<span class="date text-muted">15 May 2019</span>
            <p> Kuldeep recieved notification of the award of<a href= "https://www.nrf.gov.sg/funding-grants/nrf-fellowship-for-artificial-intelligence"> NRF Fellowship for AI </a> for the project: Provably Verified and Explainable Probabilistic Reasoning. </p>


<span class="date text-muted">9 May 2019</span>
            <p>Two papers accepted to IJCAI.The first paper explores the phase transition behavior of conjunction of cardinality and XOR constraints. Authors: Yash Pote, Saurabh Joshi, Kuldeep Meel.<br> The second paper describes a radically new approach to exact counting wherein we compute estimates that are probabilistically exact! Authors: Shubham Sharma, Kuldeep Meel. Combined with our invited paper on <a href= "https://www.comp.nus.edu.sg/~meel/Papers/CP2018msv.pdf"> #DNF </a>, this makes 3 papers that we will be presenting at IJCAI </p>

<span class="date text-muted">22 April 2019</span>
            <p>Two papers accepted to SAT 2019. The first paper introduces the first version of CrystalBall, a framework intended to allow gazing into the black box of SAT solving. Authors: Kuldeep, Mate Soos, Raghav Kulkarni.<br> The second paper discusses how model counting can be used to analyze explanations provided by tools such as ANCHOR. Authors: Kuldeep, Nina Narodytska, Aditya Shrotri, Alexey Ignatiev, and Joao Marques Silva</p>

<span class="date text-muted">11 February 2019</span>
            <p> Kuldeep  is appointed Visiting Assistant Professor in the  <a href="https://www.cse.iitb.ac.in/">Department of Computer Science and Engineering</a>  at IIT Bombay  </p>

<span class="date text-muted">2 February 2019</span>
            <p> Paper on network reliability is accepted to <a href="https://www.icasp13.snu.ac.kr/">The 13th International Conference on Applications of Statistics and Probability in Civil Engineering </a> Authors: Roger Paredes, Leonardo Duenas-Osorio, Kuldeep S. Meel, and Moshe Y. Vardi </p>

<span class="date text-muted">26 January 2019</span>
            <p>Our paper on weighted and projected sampling is accepted at <a href="https://conf.researchr.org/track/etaps-2019/tacas-2019-papers">TACAS 2019</a>. Authors: Shubham Sharma, Rahul Gupta,Subhajit Roy and Kuldeep S. Meel  </p>



</ul>
</div>
