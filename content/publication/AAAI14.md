+++
title = "Distribution-Aware Sampling and Weighted Model Counting for SAT"
date = 2014-07-01T00:00:00
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Supratik Chakraborty","Daniel J. Fremont", "Kuldeep S. Meel", "Sanjit A. Seshia", "Moshe Y. Vardi"]

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
publication = "In Proceedings of AAAI Conference on Artificial Intelligence (AAAI)."


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/AAAI14.pdf"
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

abstract = "Given a CNF formula and a weight for each assignment of values to variables, two natural problems are weighted model counting and distribution-aware sampling of satisfying assignments. Both problems have a wide variety of important applications. Due to the inherent complexity of the exact versions of the problems, interest has focused on solving them approximately. Prior work in this area scaled only to small problems in practice, or failed to provide strong theoretical guarantees, or employed a computationally-expensive maximum a posteriori probability (MAP) oracle that assumes prior knowledge of a factored representation of the weight distribution. We present a novel approach that works with a black-box oracle for weights of assignments and requires only an {\NP}-oracle (in practice, a SAT-solver) to solve both the counting and sampling problems. Our approach works under mild assumptions on the distribution of weights of satisfying assignments, provides strong theoretical guarantees, and scales to problems involving several thousand variables. We also show that the assumptions can be significantly relaxed while improving computational efficiency if a factored representation of the weights is known."

+++
