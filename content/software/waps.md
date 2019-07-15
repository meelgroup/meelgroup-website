+++
# Date this page was created.
date = 2019-04-04T00:00:00

# Project title.
title = "WAPS"

# Project summary to display on homepage.
summary = "WAPS: Weighted and Projected Sampling"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "waps.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "sampling-and-counting"]`
tags = ["sampling"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/ApproxMC.jpg"
#caption = "My caption :smile:"

code_link = "https://github.com/meelgroup/waps"

+++

Previous work on applying Knowledge compilation has focused on uniform sampling over all the variables. Since the constraints are written in high level languages such as Verilog, the popular CNF encoding schemes as Tseitin encoding introduces additional auxiliary variables. The resulting CNF formulas are not equivalent but equisatisfiable. In particular, for a formula $G$ specified in high level language we obtain a CNF formula F such that $G (X) = \\exists Y F(X,Y)$. This makes one wonder if it is possible to extend Knowledge compilation based techniques to sample over a subset of variables. Furthermore, languages such as Verilog allow specification of weights to user-defined constraints, so there is a need to sample according to the posterior distribution. In this paper, we provide affirmative question to the above two questions: We propose KUS that samples over user defined subset of variables from posterior distribution for a given prior distribution defined over product spaces.

**Relevant Papers:**

* [LPAR 2018](https://www.comp.nus.edu.sg/~meel/Papers/lpar18.pdf "LPAR 2018")
* [TACAS 2019](https://www.comp.nus.edu.sg/~meel/Papers/tacas19.pdf "TACAS 2019")
