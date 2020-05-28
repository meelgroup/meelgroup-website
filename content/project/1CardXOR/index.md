---
title: 1-CARD-XOR
summary: Phase Transition Behavior of Cardinality and XOR Constraints
tags:
- cardinality-constraints
date: "2014-01-10T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: IJCAI 2019
  url: https://www.ijcai.org/Proceedings/2019/0162.pdf
url_code: "https://github.com/meelgroup/1-CARD-XOR/"
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

The runtime performance of modern SAT solvers is deeply connected to the phase transition behavior of CNF formulas. While CNF solving has witnessed significant runtime improvement over the past two decades, the same does not hold for several other classes such as the conjunction of cardinality and XOR constraints, denoted as CARD-XOR formulas. The problem of determining satisfiability of CARDXOR formulas is a fundamental problem with wide variety of applications ranging from discrete integration in the field of artificial intelligence to maximum likelihood decoding in coding theory. The runtime behavior of random CARD-XOR formulas is unexplored in prior work. In this paper, we present the first rigorous empirical study to characterize the runtime behavior of 1-CARD-XOR formulas. We show empirical evidence of a surprising phase-transition that follows a non-linear tradeoff between CARD and XOR constraints.