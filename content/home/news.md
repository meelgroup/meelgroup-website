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
<li class="shortnews">
            <span class="date text-muted">20 June 2018</span>
            <p>I will be at IJCAI from July 12 – July 19 and at Leiden University on
July 20. I will be co-presenting <a href="http://www.comp.nus.edu.sg/~meel/Tutorials/ijcai18.html">tutorial</a> with Supratik Chakraborty at
IJCAI on July 13.</p>
</li>

#
--> 
<div id="news" class="container-fluid">
<ul class="news list-unstyled">
<li class="shortnews">
            <span class="date text-muted">13 August 2018</span>
            <p>There will be a weekly group seminar every Monday at 4pm in MR5 at SOC(NUS), starting from Aug 13. <a href="https://rahulguptakota.github.io/">     Rahul Gupta</a> will present his work in the first such session. 
		Slides will be uploaded soon after the session.</p>
</li>
       

</ul>
</div>
