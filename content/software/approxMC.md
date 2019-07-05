+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "ApproxMC"

# Project summary to display on homepage.
summary = "A hashing-based algorithm for discrete integration over finite domains."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "ApproxMC.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "sampling-and-counting"]`
tags = ["sampling-and-counting"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/ApproxMC.jpg"
#caption = "My caption :smile:"

code_link = "https://github.com/meelgroup/approxmc"

+++

ApproxMC is a hashing-based algorithm for approximate discrete integration over finite domains and provides ($\epsilon$,$\delta$) guarantees. This implementation handles the case when the function is implicitely defined by SAT formula. To the best of our knowledge, the current implementation has the best runtime performance among approximate counting algorithms. We are actively improving algorithm as well as implementation and would love to hear your feedback.

**Relevant Papers:**

* [IJCAI 2016](https://www.comp.nus.edu.sg/~meel/Papers/ijcai16_counting.pdf "IJCAI 2016")
* [Constraints 2016](https://www.comp.nus.edu.sg/~meel/Papers/constraints16.pdf "Constraints 2016")
* [CP 2013](https://www.comp.nus.edu.sg/~meel/Papers/CP2013.pdf "CP 2013")

