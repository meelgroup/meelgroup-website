+++
title = "Assessing Heuristic Machine Learning Explanations with Model Counting  "
date = 2019-05-05T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nina Narodytska","Aditya Shrotri","Kuldeep S. Meel","Alexey Ignatiev","Joao Marques Silva"] 

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
publication = "In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
#url_pdf = "https://bishwamittra.github.io/publication/imli-ghosh.pdf"
#url_preprint = ""
#url_code = ""
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
abstract = "Machine Learning (ML) models are widely used in decision making procedures in finance, medicine, education, etc. In these areas, ML outcomes can directly affect humans, e.g.\\ by deciding whether a person should get a loan or be released from prison. Therefore, we cannot blindly rely on black box ML models and need to explain the decisions made by them. This motivated the development of a variety of ML-explainer systems, concrete examples of which include LIME and its successor ANCHOR. Due to the heuristic nature of explanations produced by existing tools, it is necessary to validate them. In this work, we propose a SAT-based method to assess the quality of explanations produced by ANCHOR We encode a trained ML model and an explanation for a given prediction as a propositional formula. Then, by using a state-of-the-art approximate model counter, we estimate the quality of the provided explanation as the number of solutions supporting it."

+++
