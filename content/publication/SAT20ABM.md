+++
title = "On the Sparsity of XORs in Approximate Model Counting"
date = 2020-05-19T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Durgesh Agrawal", "Bhavishya", "Kuldeep S. Meel"]

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
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/sat20-adm.pdf"
#url_preprint = "https://arxivorg/abs/2005.04850"
#url_code = "https://github.com/meelgroup/duriansat"
url_dataset = "http://doi.org/10.5281/zenodo.3792748"
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
abstract = "Given a Boolean formula F, the problem of model counting, also referred to as #SAT, is to compute the number of solutions of F. The hashing-based techniques for approximate counting have emerged as a dominant approach, promising achievement of both scalability and rigorous theoretical guarantees. The standard construction of strongly 2-universal hash functions employs dense XORs (i.e., involving half of the variables in expectation), which is widely known to cause degradation in the runtime performance of state of the art SAT solvers. Consequently, the past few years have witnessed an intense activity in the design of sparse XORs as hash functions. Such constructions have been proposed with beliefs to provide runtime performance improvement along with theoretical guarantees similar to that of dense XORs. The primary contribution of this paper is a rigorous theoretical and empirical analysis to understand the effect of the sparsity of XORs. In contradiction to prior beliefs of applicability of analysis for sparse hash functions to all the hashing-based techniques, we prove a contradictory result. We show that the best-known bounds obtained for sparse XORs are still too weak to yield theoretical guarantees for a large class of hashing- based techniques, including the state of the art approach ApproxMC3. We then turn to a rigorous empirical analysis of the performance benefits of sparse hash functions. To this end, we first design, to the best of our knowledge, the most efficient algorithm called SparseCount2 using sparse hash functions, which achieves at least up to two orders of magnitude performance improvement over its predecessor. Contradicting the current beliefs, we observe that SparseCount2 still falls short of ApproxMC3 in runtime performance despite the usage of dense XORs in ApproxMC3. In conclusion, our work showcases that the question of whether it is possible to use short XORs to achieve scalability while providing strong theoretical guarantees is still wide open. "

+++
