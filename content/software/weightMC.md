+++
# Date this page was created.
date = 2014-07-27T00:00:00

# Project title.
title = "WeightMC"

# Project summary to display on homepage.
summary = "A weighted model counter over Boolean domains."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "WeightMC.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "sampling-and-counting"]`
tags = ["sampling-and-counting"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/WeightMC.jpg"
#caption = "My caption :smile:"

code_link = "https://bitbucket.org/kuldeepmeel/weightmc"

+++

WeightMC is hashing-based algorithm for weighted counting (discrete integration) over Boolean domains. It takes a CNF formula and weight function as inputs and returns weighted count. In contrast to previous attempts to develop weighted counting that rely on use of Optimization oracles, WeightMC only uses feasibility oracle. A simple reworking of this algorithm was used by Belle et al to predicate delays in UK transportation network.

**Relevant Papers:**

* [AAAI 2014](https://www.comp.nus.edu.sg/~meel/Papers/AAAI14.pdf "AAAI 2014")

