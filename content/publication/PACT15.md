+++
title = "Design and Verification of Distributed Phasers"
date = 2016-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Karthik","Murthy","Sri Raj","Paul","Kuldeep S. Meel", "Tiago Cogumbreiro", "John Mellor-Crummey"]

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
publication = "In *Proceedings of International European Conference on Parallel and Distributed Computing (Euro-Par)*"

abstract = "A phaser is an expressive synchronization construct that unifies collective and point-to-point coordination with dynamic registration of parallel tasks. Each task can participate in a phaser as a signaler, a waiter, or both. The participants in a phaser may change over time as tasks are added and deleted. In this paper, we present a highly concurrent and scalable design of phasers for a distributed memory environment. Our design for a distributed phaser employs a pair of skip lists augmented with the ability to collect and propagate synchronization signals. To enable a high degree of concurrency, addition and deletion of participant tasks are performed in two phases: a \"fast single-link-modify\" step followed by multiple hand-over-hand \"lazy multi-link-modify\" steps. Verifying highly-concurrent protocols is difficult. We analyze our design for a distributed phaser using the SPIN model checker. A straight-forward approach to model checking a distributed phaser operation requires an infeasibly large state space. To address this issue, we employ a novel \"message-based\" model checking scheme to enable a non- approximate complete model checking of our phaser design. We guarantee the semantic properties of phaser operations by ensuring that a set of linear temporal logic formulae are valid during model checking. We also present complexity analysis of the cost of synchronization and structural operations."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/PACT15.pdf"
#url_preprint = ""
url_code = "http://srp7.web.rice.edu/phaser/"
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
