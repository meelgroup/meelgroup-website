+++
# Date this page was created.
date = 2019-07-07T00:00:00

# Project title.
title = "CrystalBall"

# Project summary to display on homepage.
summary = "A hashing-based approximate sampler for weighted CNF formulas."

# Optional image to display on homepage (relative to `static/img/` folder).
# image_preview = "WeightGen.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "sampling-and-counting"]`
tags = ["sampling-and-counting"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/WeightGen.jpg"
#caption = "My caption :smile:"

code_link = "https://github.com/msoos/cryptominisat/tree/crystalball"

+++

Boolean satisfiability is a fundamental problem in computerscience with a wide range of applications including planning, configurationmanagement, design and verification of software/hardware systems. Modern SAT solvers achieve scalability and ro-bustness with sophisticated heuristics that are challenging to understandand explain. We propose to view modern conflict-driven clause learning (CDCL) solvers as a composition of classifiers and regressors for different tasks such as branching, clause memory management, and restarting. The current version of CrystalBall focuses on deriving a classifier to keep or throw away a learned clause. In a departure from recent machine learning based techniques, CrystalBall employs supervised learning anduses extensive, multi-gigabyte data extracted from runs of a single SAT solver to perform predictive analytics.

**Relevant Papers:**

* [SAT 2019](https://www.msoos.org/wordpress/wp-content/uploads/2019/06/sat19-skm.pdf "SAT 2019")
