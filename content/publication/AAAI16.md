+++
title = "Approximate Probabilistic Inference via Word-Level Counting "
date = 2016-06-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Supratik Chakraborty", "Kuldeep S. Meel", "Rakesh Mistry", "Moshe Y. Vardi"]

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
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/AAAI16.pdf"
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

abstract = "Hashing-based model counting has emerged as a promising approach for large-scale probabilistic inference on graphical models. A key component of these techniques is the use of xor-based 2-universal hash functions that operate over Boolean domains. Many counting problems arising in probabilistic inference are, however, naturally encoded over fi- nite discrete domains. Techniques based on bit-level (or Boolean) hash functions require these problems to be propositionalized, making it impossible to leverage the remarkable progress made in SMT (Satisfiability Modulo Theory) solvers that can reason directly over words (or bit-vectors). In this work, we present the first approximate model counter that uses word-level hashing functions, and can directly leverage the power of sophisticated SMT solvers. Empirical evaluation over an extensive suite of benchmarks demonstrates the promise of the approach."

+++
