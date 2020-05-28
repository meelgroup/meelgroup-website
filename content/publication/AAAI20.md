+++
title = "A MaxSAT-based Framework for Group Testing"
date = 2020-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lorenzo Ciampiconi","Bishwamittra Ghosh", "Jonathan Scarlett", "Kuldeep S. Meel"]

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
publication = "In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://bishwamittra.github.io/publication/aaai_2020/AAAI-CiampiconiL.690.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/mgt"
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

abstract ="The success of MaxSAT (maximum satisfiability) solving in recent years has motivated researchers to apply MaxSAT solvers in diverse discrete combinatorial optimization problems. Group testing has been studied as a combinatorial optimization problem, where the goal is to find defective items among a set of items by performing sets of tests on items. In this paper, we propose a MaxSAT-based framework, called MGT, that solves group testing, in particular, the decoding phase of non-adaptive group testing. We extend this approach to the noisy variant of group testing, and propose a compact MaxSAT-based encoding that guarantees an optimal solution. Our extensive experimental results show that MGT can solve group testing instances of 10000 items with 3% defectivity, which no prior work can handle to the best of our knowledge. Furthermore, MGT has better accuracy than the LP-based approach. We also discover an interesting phase transition behavior in the runtime, which reveals the easy-hard-easy nature of group testing."
+++
