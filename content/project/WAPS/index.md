---
title: WAPS
summary: "WAPS: Weighted and Projected Sampling"
tags:
- sampling
date: "2019-04-04T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: LPAR 2018
  url: https://www.comp.nus.edu.sg/~meel/Papers/lpar18.pdf
- icon: file
  icon_pack: far
  name: TACAS 2019
  url: https://www.comp.nus.edu.sg/~meel/Papers/tacas19.pdf
url_code: "https://github.com/meelgroup/waps"
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

Previous work on applying Knowledge compilation has focused on uniform sampling over all the variables. Since the constraints are written in high level languages such as Verilog, the popular CNF encoding schemes as Tseitin encoding introduces additional auxiliary variables. The resulting CNF formulas are not equivalent but equisatisfiable. In particular, for a formula $G$ specified in high level language we obtain a CNF formula F such that $G (X) = \\exists Y F(X,Y)$. This makes one wonder if it is possible to extend Knowledge compilation based techniques to sample over a subset of variables. Furthermore, languages such as Verilog allow specification of weights to user-defined constraints, so there is a need to sample according to the posterior distribution. In this paper, we provide affirmative question to the above two questions: We propose KUS that samples over user defined subset of variables from posterior distribution for a given prior distribution defined over product spaces.
