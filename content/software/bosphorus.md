+++
# Date this page was created.
date = 2019-01-05T00:00:00

# Project title.
title = "Bosphorus"

# Project summary to display on homepage.
summary = "An ANF and CNF simplifier and converter."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "Bosphorus.png"

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

Algebraic Normal Form (ANF) and Conjunctive Normal Form (CNF) are commonly used to encode problems in Boolean algebra. ANFs are typically solved via Gröbner basis algorithms, often using more memory than is feasible; while CNFs are solved using SAT solvers, which cannot exploit the algebra of polynomials naturally. We propose a paradigm that bridges between ANF and CNF solving techniques: the techniques are applied in an iterative manner to learn facts to augment the original problems. Experiments on over 1,100 benchmarks arising from four different applications domains demonstrate that learnt facts can significantly improve runtime and enable more benchmarks to be solved.

**Relevant Papers:**

* [DATE 2019](https://www.comp.nus.edu.sg/~meel/Papers/date-cscm19.pdf "DATE 2019")

