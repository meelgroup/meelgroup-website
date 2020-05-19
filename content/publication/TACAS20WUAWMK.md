+++
title = "A Study of Symmetry Breaking Predicates and Model Counting"
date = 2020-04-04T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wenxi Wang", "Muhammad Usman", "Alyas Almaawi", "Kaiyuan Wang", "Sarfraz Khurshid", "Kuldeep S. Meel"]

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
publication = "In *Proceedings of Tools and Algorithms for the Construction and Analysis of Systems (TACAS)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/tacas20.pdf"
#url_preprint = ""
#url_code = "https://github.com/meelgroup/waps"
#url_dataset = ""
#url_project = ""
#url_slides = "files/slides/TACAS19.pdf"
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
abstract = "Propositional model counting is a classic problem that has recently witnessed many technical advances and novel applications. While the basic model counting problem requires computing the number of all solutions to the given formula, in some important application scenarios, the desired count is not of all solutions, but instead, of all unique solutions up to isomorphism. In such a scenario, the user herself must try to either use the full count that the model counter returns to compute the count up to isomorphism, or ensure that the input formula to the model counter adequately captures the symmetry breaking predicates so it can directly report the count she desires. We study the use of CNF-level and domain-level symmetry breaking predicates in the context of the state-of-the-art in model counting, specifically the leading approximate model counter ApproxMC and the recently introduced exact model counter ProjMC. As benchmarks, we use a range of problems, including structurally complex specifications of software systems and constraint satisfaction problems. The results show that while it is sometimes feasible to compute the model counts up to isomorphism using the full counts that are computed by the model counters, doing so suffers from poor scalability. The addition of symmetry breaking predicates substantially assists model counters. Domain-specific predicates are particularly useful, and in many cases can provide full symmetry breaking to enable highly efficient model counting up to isomorphism. We hope our study motivates new research on designing model counters that directly account for symmetries to facilitate further applications of model counting."

+++
