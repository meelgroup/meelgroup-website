---
title: UniGen
summary: An algorithm to generate uniform samples subject to given set of constraints.
tags:
- sampling-and-counting
date: "2019-05-01T00:00:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: CardXOR
  focal_point: Smart

links:
- icon: file
  icon_pack: far
  name: TACAS 2015
  url: https://www.cs.toronto.edu/~meel/Papers/Tacas15.pdf
- icon: file
  icon_pack: far
  name: DAC 2014
  url: https://www.cs.toronto.edu/~meel/Papers/DAC2014.pdf
- icon: file
  icon_pack: far
  name: CAV 2013
  url: https://www.cs.toronto.edu/~meel/Papers/cav13.pdf
url_code: "https://bitbucket.org/kuldeepmeel/unigen"
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

UniGen is a hashing-based algorithm to generate uniform samples subject to given set of constraints. The primary application of UniGen is in random stimuli generation for hardware and software verification. The current version of the tool has been developed over the years and is parallelizable without losing theoretical guarantees.
