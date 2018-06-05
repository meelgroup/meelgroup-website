+++
title = "On Hashing-Based Approaches to Approximate DNF-Counting "
date = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kuldeep S. Meel", "Aditya A. Shrotri", "Moshe Y. Vardi"]

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
publication = "In *Proceedings of IARCS Annual Conference on Foundations of Software Technology and Theoretical Computer Science, 2017.*"
#publication_short = "In *AAAI*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/fsttcs17.pdf"
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

+++
<button class="btn btn-default btn-xs" type="button" data-toggle="collapse" data-target="#abstract_DMPV17">
Abstract</button>
<div id="abstract_DMPV17" class="collapse">
Propositional model counting is a fundamental problem in artificial intelligence with a wide variety of applications, such as probabilistic inference, decision making under uncertainty, and probabilistic databases. Consequently, the problem is of theoretical as well as practical interest. When the constraints are expressed as DNF formulas, Monte Carlo-based techniques have been shown to provide a fully polynomial randomized approximation scheme (FPRAS). For CNF constraints, hashing-based approximation techniques have been demonstrated to be highly successful. Furthermore, it was shown that hashing-based techniques also yield an FPRAS for DNF counting without usage of Monte Carlo sampling. Our analysis, however, shows that the proposed hashing-based approach to DNF counting provides poor time complexity compared to the Monte Carlo-based DNF counting techniques. Given the success of hashing-based techniques for CNF constraints, it is natural to ask: Can hashing-based techniques provide an efficient FPRAS for DNF counting? In this paper, we provide a positive answer to this question. To this end, we introduce two novel algorithmic techniques: Symbolic Hashing and Stochastic Cell Counting, along with a new hash family of Row-Echelon hash functions. These innovations allow us to design a hashing-based FPRAS for DNF counting of similar complexity as that of prior works. Furthermore, we expect these techniques to have potential applications beyond DNF counting.
</div>
