---
title: Bosphorus
summary: An ANF and CNF simplifier and converter.
tags:
- sampling-and-counting
date: "2019-01-05T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: DATE 2019
  url: https://www.cs.toronto.edu/~meel/Papers/date-cscm19.pdf
url_code: "https://github.com/meelgroup/bosphorus"
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

Algebraic Normal Form (ANF) and Conjunctive Normal Form (CNF) are commonly used to encode problems in Boolean algebra. ANFs are typically solved via Gröbner basis algorithms, often using more memory than is feasible; while CNFs are solved using SAT solvers, which cannot exploit the algebra of polynomials naturally. We propose a paradigm that bridges between ANF and CNF solving techniques: the techniques are applied in an iterative manner to learn facts to augment the original problems. Experiments on over 1,100 benchmarks arising from four different applications domains demonstrate that learnt facts can significantly improve runtime and enable more benchmarks to be solved.
