+++
title = " IMLI: An Incremental Framework for MaxSAT-Based Learning of Interpretable Classification Rules "
date = 2019-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bishwamittra Ghosh", "Kuldeep S. Meel"] 

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
publication = "In *Proceedings of AAAI/ACM Conference on AI, Ethics, and Society (AIES)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://bishwamittra.github.io/publication/imli-ghosh.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/mlic"
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
abstract = "The wide adoption of machine learning in the critical domains such as medical diagnosis, law, education had propelled the need for interpretable techniques due to the need for end user to understand the reasoning behind decisions due to learning systems. The computational intractability of interpretable learning led practitioners to design heuristic techniques, which fail to provide sound handles to tradeoff accuracy and interpretability. Motivated by the success of Max-SAT solvers over the past decade, recently MaxSAT-based approach, called MLIC, was proposed that seeks to reduce the problem of learning interpretable rules expressed in Conjunctive Normal Form (CNF) to a MaxSAT query. While MLIC was shown to achieve accuracy similar to that of other state of the art black-box classifiers while generating small interpretable CNF formulas, the runtime performance of MLIC is significantly lagging and renders approach unusable in practice. In this context, authors raised the question: Is it possible to achieve the best of both worlds, i.e. a sound framework for interpretable learning that can take advantage of MaxSAT solvers while scaling to real-world instances? In this paper, we take a step towards answering the above question in affirmation. We propose an incremental approach to Max-SAT based framework that achieves scalable runtime performance via partition-based training methodology. Extensive experiments on benchmarks arising from UCI repository demonstrate that IMLI achieves up to three orders of magnitude runtime improvement without loss of accuracy and interpretability. "

+++
