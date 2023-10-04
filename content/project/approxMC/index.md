---
title: ApproxMC
summary: A hashing-based algorithm for discrete integration over finite domains.
tags:
- sampling-and-counting
date: "2019-07-09T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: IJCAI 2016
  url: https://www.cs.toronto.edu/~meel/Papers/ijcai16_counting.pdf
- icon: file
  icon_pack: far
  name: Constraints 2016
  url: https://www.cs.toronto.edu/~meel/Papers/constraints16.pdf
- icon: file
  icon_pack: far
  name: CP 2013
  url: https://www.cs.toronto.edu/~meel/Papers/CP2013.pdf
url_code: "https://github.com/meelgroup/approxmc"
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

ApproxMC is a hashing-based algorithm for approximate discrete integration over finite domains and provides ($\epsilon$,$\delta$) guarantees. This implementation handles the case when the function is implicitely defined by SAT formula. To the best of our knowledge, the current implementation has the best runtime performance among approximate counting algorithms. We are actively improving algorithm as well as implementation and would love to hear your feedback.
