---
title: CrystalBall
summary: A framework to provide white-box access to the execution of SAT solver.
tags:
- sampling-and-counting
date: "2019-07-07T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: SAT 2019
  url: https://www.msoos.org/wordpress/wp-content/uploads/2019/06/sat19-skm.pdf
url_code: "https://github.com/msoos/cryptominisat/tree/crystalball"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Boolean satisfiability is a fundamental problem in computerscience with a wide range of applications including planning, configurationmanagement, design and verification of software/hardware systems. Modern SAT solvers achieve scalability and ro-bustness with sophisticated heuristics that are challenging to understandand explain. We propose to view modern conflict-driven clause learning (CDCL) solvers as a composition of classifiers and regressors for different tasks such as branching, clause memory management, and restarting. The current version of CrystalBall focuses on deriving a classifier to keep or throw away a learned clause. In a departure from recent machine learning based techniques, CrystalBall employs supervised learning anduses extensive, multi-gigabyte data extracted from runs of a single SAT solver to perform predictive analytics. Read this [blog post](https://www.msoos.org/2019/06/crystalball-sat-solving-data-gathering-and-machine-learning/) for more details.