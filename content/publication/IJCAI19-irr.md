+++
title = " Interpretable Classification Rules in Relaxed Logical Form "
date = 2019-06-23T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bishwamittra Ghosh", "Dmitry Malioutov", "Kuldeep S. Meel"] 

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "IJCAI  workshop on XAI (Explainable Artificial Intelligence) and DSO (Data Science meets Optimization)"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://bishwamittra.github.io/publication/irr-ghosh.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/irr"
#url_dataset = ""
#url_project = ""
#url_slides = ""
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
abstract = "Interpretability has become a central thread in ML research. As ML algorithms continue to permeate critical application domains such as medicine, legal, and transportation, it becomes increasingly important to allow human domain experts to understand and interact with ML solutions. ML algorithms that produce predictions in the form of rules are arguably some of the most interpretable ones, but their discrete combinatorial structure makes them computationally hard to learn. Here we generalize the widely popular CNF rules and introduce relaxed-CNF rules. These rules are much more flexible in terms of fitting data (have higher capacity) but about as interpretable to people as the traditional ones. We consider relaxed definitions of standard OR/AND operators which allow exceptions in the construction of a clause and also in the selection of clauses in a rule. We first describe an exact ILP solution, which is computationally expensive. We then propose an incremental solution, which allows us to generate accurate interpretable relaxed-CNF rules with significantly improved runtime performance."

+++