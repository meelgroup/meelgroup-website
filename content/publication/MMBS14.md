+++
title = "ADHA: Automatic Data layout framework for Heterogeneous Architectures"
date = 2014-08-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Deepak Majeti", "Kuldeep S. Meel", "Raj Barik", "Vivek Sarkar"]

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
publication = "In *Proceedings of Parallel Architecture and Compilation Techniques (PACT)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://arxiv.org/pdf/1407.4859.pdf"
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
abstract = "Data layouts play a crucial role in determining the performance of a given application running on a given architecture. Existing parallel programming frameworks for both multicore and heterogeneous systems leave the onus of selecting a data layout to the programmer. Therefore, shifting the burden of data layout selection to optimizing compilers can greatly enhance programmer productivity and application performance. In this work, we introduce ADHA: a two-level hierarchal formulation of the data layout problem for modern heterogeneous architectures. We have created a reference implementation of ADHA in the Heterogeneous Habanero-C (H2C) parallel programming system. ADHA shows significant performance benefits of up to 6.92X compared to manually specified layouts for two benchmark programs running on a CPU+GPU heterogeneous platform."

+++
