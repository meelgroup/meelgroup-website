+++
title = "WAPS: Weighted and Projected Sampling "
date = 2019-04-04T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Rahul Gupta"," Shubham Sharma", "Kuldeep S. Meel"]

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
publication = "In *Proceedings of Tools and Algorithms for the Construction and Analysis of Systems (TACAS)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/tacas19.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/waps"
#url_dataset = ""
#url_project = ""
url_slides = "files/slides/TACAS19.pdf"
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
abstract = "Previous work on applying Knowledge compilation has focused on uniform sampling over all the variables. Since the constraints are written in high level languages such as Verilog, the popular CNF encoding schemes as Tseitin encoding introduces additional auxiliary variables. The resulting CNF formulas are not equivalent but equisatisfiable. In particular, for a formula $G$ specified in high level language we obtain a CNF formula F such that $G (X) = \\exists Y F(X,Y)$. This makes one wonder if it is possible to extend Knowledge compilation based techniques to sample over a subset of variables. Furthermore, languages such as Verilog allow specification of weights to user-defined constraints, so there is a need to sample according to the posterior distribution. In this paper, we provide affirmative question to the above two questions: We propose KUS that samples over user defined subset of variables from posterior distribution for a given prior distribution defined over product spaces."

+++
