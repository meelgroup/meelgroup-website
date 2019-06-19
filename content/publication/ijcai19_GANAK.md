+++
title = "GANAK: A Scalable Probabilistic Exact Model Counter"
date = 2019-05-21T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shubham Sharma", "Subhajit Roy", "Mate Soos", "Kuldeep S. Meel"]

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
publication = "In *Proceedings International Joint Conference on Artificial Intelligence (IJCAI)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = ""
#url_preprint = ""
#url_code = "https://github.com/meelgroup/ganak"
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

abstract = "Given a Boolean formula $F$, the problem of  model counting, also referred to as #SAT, seeks to compute the number of solutions of $F$. Model counting is a fundamental problem with a wide variety of applications ranging from planning, quantified information flow to probabilistic reasoning and the like. The modern #SAT solvers tend to be either based on static decomposition, dynamic decomposition, or a hybrid of the two. Despite dynamic decomposition based #SAT solvers sharing much of their architecture with SAT solvers, the core design and heuristics of dynamic decomposition-based #SAT solvers has remained constant for over a decade. In this paper, we revisit the architecture of the state-of-the-art dynamic decomposition-based #SAT tool, sharpSAT, and demonstrate that by introducing a new notion of probabilistic component caching and the usage of universal hashing for exact model counting along with the development of several new heuristics can lead to significant performance improvement over state-of-the-art model-counters. In particular, we develop GANAK, a new scalable probabilistic exact model counter that outperforms state-of-the-art exact and approximate model counters sharpSAT and ApproxMC3 respectively, both in terms of PAR-2 score and the number of instances solved. Furthermore, in our experiments, the model count returned by GANAK was equal to the exact model count for all the benchmarks. Finally, we observe that recently proposed preprocessing techniques for model counting benefit exact model counters while hurting the performance of approximate model counters."

+++
