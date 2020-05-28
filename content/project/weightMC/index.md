---
title: WeightMC
summary: A weighted model counter over Boolean domains.
tags:
- sampling-and-counting
date: "2014-07-27T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: AAAI 2014
  url: https://www.comp.nus.edu.sg/~meel/Papers/AAAI14.pdf
url_code: "https://bitbucket.org/kuldeepmeel/weightmc"
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

WeightMC is hashing-based algorithm for weighted counting (discrete integration) over Boolean domains. It takes a CNF formula and weight function as inputs and returns weighted count. In contrast to previous attempts to develop weighted counting that rely on use of Optimization oracles, WeightMC only uses feasibility oracle. A simple reworking of this algorithm was used by Belle et al to predicate delays in UK transportation network.
