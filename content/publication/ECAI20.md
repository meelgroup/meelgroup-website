+++
title = "Classification Rules in Relaxed Logical Form"
date = 2020-01-23T00:00:00

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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of ECAI*"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://bishwamittra.github.io/publication/ecai_2020/paper.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = "files/slides/AAAI19_hardness.pdf"
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

abstract = "ML algorithms that produce rule-based predictions in Conjunctive Normal form (CNF) or in Disjunctive Normal form (DNF) are arguably some of the most interpretable ones. Although CNF/DNF rules are considered interpretable in practice, propositional logic has other very interpretable representations which are more expressive. In this paper, we generalize CNF/DNF rules and introduce relaxed-CNF rules, which is motivated by the popular usage of checklists in the medical domain. We consider relaxed definitions of standard OR/AND operators which allow exceptions in the construction of a clause and also in the selection of clauses in a rule. While the combinatorial structure of relaxed-CNF rules offers exponential succinctness, the naive learning techniques are computationally expensive. The primary contribution of this paper is to propose a novel incremental mini-batch learning procedure, called CRR, that employs advances in the combinatorial solvers and efficiently learns relaxed-CNF rules. Our experimental analysis demonstrates that CRR can generate relaxed-CNF rules which are more accurate compared to CNF rules and sparser compared to decision lists."

+++
