+++
title = "On the Hardness of Probabilistic Inference Relaxations"
date = 2019-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Supratik Chakraborty", "Kuldeep S. Meel", "Moshe Y. Vardi"]

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
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/aaai19-cmv.pdf"
#url_preprint = ""
#url_code = ""
#url_dataset = ""
#url_project = ""
url_slides = "files/slides/AAAI19_hardness.pdf"
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

abstract = "Probabilistic inference is increasingly being used in applications that compute with uncertain data. A promising approach to inference that has attracted recent attention exploits its inter-reducibility with model counting. Since probabilistic inference and model counting are #P-complete, various relaxations are used in practice, with the hope that these relaxations lend themselves to efficient computation while also providing rigorous approximation guarantees. In this paper, we show that contrary to commonly held belief, several relaxations used in the probabilistic inference literature do not really lead to computational efficiency in a complexity theoretic sense. Our arguments proceed by showing the corresponding relaxed notions of counting to be computationally hard. We argue that approximate counting (and hence, inference) with multiplicative tolerance and probabilistic guarantees of correctness is the only class of relaxations that provably simplifies the problem, given access to an NP-oracle. Finally, we show that for applications that compare probability estimates with a threshold, a new notion of relaxation with gaps between low and high thresholds can be used. This new relaxation allows efficient decision making in practice, given access to an NP-oracle, while also bounding the approximation error. "

+++
