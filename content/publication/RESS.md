+++
title = "Network Reliability Estimation in Theory and Practice "
date = 2018-05-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Kuldeep S. Meel","Roger Paredes", "Leonardo Duenas-Osorio","Moshe Y. Vardi"] 

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Submitted to Reliability Engineering and System Safety*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://arxiv.org/pdf/1806.00917.pdf"
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
abstract = "As engineered systems expand, become more interdependent, and operate in real-time, reliability assessment is indispensable to support investment and decision making. However, network reliability problems are known to be #P-complete, a computational complexity class largely believed to be intractable. The computational intractability of network reliability motivates our quest for reliable approximations. Based on their theoretical foundations, available methods can be grouped as follows: (i) exact or bounds, (ii) guarantee-less sampling, and (iii) probably approximately correct (PAC). Group (i) is well regarded due to its useful byproducts, but it does not scale in practice. Group (ii) scales well and verifies desirable properties, such as the bounded relative error, but it lacks error guarantees. Group (iii) is of great interest when precision and scalability are required, as it harbors computationally feasible approximation schemes with PAC-guarantees. We give a comprehensive review of classical methods before introducing modern techniques and our developments. We introduce K-RelNet, an extended counting-based estimation method that delivers PAC-guarantees for the K-terminal reliability problem. Then, we test methods' performance using various benchmark systems. We highlight the range of application of algorithms and provide the foundation for future resilience engineering as it increasingly necessitates methods for uncertainty quantification in complex systems."

+++
