+++
title = "BIRD: Engineering an Efficient CNF-XOR SAT Solver and its Applications to Approximate Model Counting"
date = 2019-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Mate Soos", "Kuldeep S. Meel"]

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
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/aaai19-sm.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/approxmc"
#url_dataset = ""
#url_project = ""
url_slides = "files/slides/AAAI19_BIRD.pdf"
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

abstract = "Given a Boolean formula F, the problem of model counting, also referred to as #SAT is to compute the number of solutions of F. Model counting is a fundamental problem in artificial intelligence with a wide range of applications including probabilistic reasoning, decision making under uncertainty, quantified information flow, and the like. Motivated by the success of SAT solvers, there has been surge of interest in the design of hashing-based techniques for approximate model counting for the past decade. We profiled the state of the art approximate model counter ApproxMC3 and observed that over 99.99% of time is consumed by the underlying SAT solver, CryptoMinisat. This observation motivated us to ask: Can we design an efficient underlying CNF-XOR SAT solver that can take advantage of the structure of hashing-based algorithms and would this lead to an efficient approximate model counter? The primary contribution of this paper is an affirmative answer to the above question. We present a novel architecture, called BIRD, to handle CNF-XOR formulas arising from hashing-based techniques. The resulting hashing-based approximate model counter, called ApproxMC3, employs the BIRD framework in its underlying SAT solver, CryptoMinisat. To the best of our knowledge, we conducted the most comprehensive study of evaluation performance of counting algorithms involving 1896 benchmarks with computational effort totaling 86400 computational hours. Our experimental evaluation demonstrates significant runtime performance improvement for ApproxMC3 over ApproMC2. In particular, we solve 648 benchmarks more than ApproMC2, the state of the art approximate model counter and for all the formulas where both ApproMC2 and ApproxMC3 did not timeout and took more than 1 seconds, the mean speedup is 284.40 -- more than two orders of magnitude. "

+++
