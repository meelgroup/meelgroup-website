+++
title = "Designing New Phase Selection Heuristics"
date = 2020-05-18T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Arijit Shaw", "Kuldeep S. Meel"]

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
url_pdf = "files/papers/sat20_lsids.pdf"
#url_preprint = "https://arxiv.org/abs/2005.04850"
#url_code = "https://github.com/meelgroup/duriansat"
#url_dataset = "https://doi.org/10.5281/zenodo.3817476"
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
abstract = "CDCL-based SAT solvers have transformed the field of automated reasoning owing to their demonstrated efficiency at handling problems arising from diverse domains. The success of CDCL solvers is owed to the design of clever heuristics that enable the tight coupling of different components. One of the core components is phase selection, wherein the solver, during branching, decides the polarity of the branch to be explored for a given variable. Most of the state-of-the-art CDCL SAT solvers employ phase-saving as a phase selection heuristic, which was proposed to address the potential inefficiencies arising from far-backtracking. In light of the emergence of chronological backtracking in CDCL solvers, we re-examine the efficiency of phase saving. Our empirical evaluation leads to a surprising conclusion: The usage of phase saving and random selection of polarity during chronological backtracking leads to indistinguishable runtime performance in terms of instances solved and PAR-2 score. We introduce Decaying Polarity Score (DPS) to capture the trend of the polarities attained by the variable, and upon observing lack of performance improvement due to DPS, we turn to a more sophisticated heuristic seeking to capture the activity of literals and the trend of polarities: Literal State Independent Decaying Sum (LSIDS). We find the 2019 winning SAT solver, Maple_LCM_Dist_ChronoBTv3, augmented with LSIDS solves 6 more instances while achieving a reduction of over 125 seconds in PAR-2 score, a significant improvement in the context of the SAT competition."

+++
