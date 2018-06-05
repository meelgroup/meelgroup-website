+++
title = "Algorithmic Improvements in Approximate Counting for Probabilistic Inference: From Linear to Logarithmic SAT Calls  "
date = 2016-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kuldeep S. Meel", "Supratik Chakraborty", "Moshe Y. Vardi"]

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
publication = "In *Proceedings of International Joint Conference on Artificial Intelligence (IJCAI), 2016.*"
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
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/ijcai16_counting.pdf"
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
Probabilistic inference via model counting has emerged as a scalable technique with strong formal guarantees, thanks to recent advances in hashing-based approximate counting. State-of-the-art hashing-based counting algorithms use an {\NP} oracle, such that the number of oracle invocations grows linearly in the number of variables n in the input constraint. We present a new approach to hashing-based approximate model counting in which the number of oracle invocations grows logarithmically in $n$, while still providing strong theoretical guarantees. Our experiments show that the new approach outperforms state-of-the-art techniques for approximate counting by 1-2 orders of magnitude in running time.
</div>
