+++
title = "From Weighted to Unweighted Model Counting "
date = 2015-07-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Supratik Chakraborty","Dror Fried","Kuldeep S. Meel",  "Moshe Y. Vardi"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of International Joint Conference on Artificial Intelligence (IJCAI)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/ijcai15.pdf"
#url_preprint = ""
url_code = "https://bitbucket.org/kuldeepmeel/weightcount/src/master/"
#url_dataset = ""
#url_project = ""
url_slides = "files/slides/Talk.pdf"
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"
abstract = "The recent surge of interest in reasoning about probabilistic graphical models has led to the development of various techniques for probabilistic reasoning. Of these, techniques based on weighted model counting are particularly interesting since they can potentially leverage recent advances in unweighted model counting and in propositional satisfiability solving. In this paper, we present a new approach to weighted model counting via reduction to unweighted model counting. Our reduction, which is polynomial-time and preserves the normal form (CNF/DNF) of the input formula, allows us to exploit advances in unweighted model counting to solve weighted model counting instances. Experiments with weighted model counters built using our reduction indicate that these counters performs much better than a state-of-the-art weighted model counter."

+++
