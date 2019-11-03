+++
title = " Embedding Symbolic Knowledge into Deep Networks "
date = 2019-09-30T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yaqi Xie", "Ziwei Xu", "Mohan S. Kankanhalli", "Kuldeep S. Meel", "Harold Soh"] 

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
publication = "In *Advances in Neural Information Processing Systems(NeurIPS)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://arxiv.org/abs/1909.01161"
#url_preprint = ""
url_code = "https://github.com/ZiweiXU/LENSR"
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
abstract = "In this work, we aim to leverage prior symbolic knowledge to improve the performance of deep models. We propose a graph embedding network that projects propositional formulae (and assignments) onto a manifold via an augmented Graph Convolutional Network (GCN). To generate semantically-faithful embeddings, we develop techniques to recognize node heterogeneity, and semantic regularization that incorporate structural constraints into the embedding. Experiments show that our approach improves the performance of models trained to perform entailment checking and visual relation prediction. Interestingly, we observe a connection between the tractability of the propositional theory representation and the ease of embedding. Future exploration of this connection may elucidate the relationship between knowledge compilation and vector representation learning."

+++
