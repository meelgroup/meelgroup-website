+++
# Date this page was created.
date = 2019-06-15T00:00:00

# Project title.
title = "GANAK"

# Project summary to display on homepage.
summary = "GANAK: A Scalable Probabilistic Exact Model Counter"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "ganak.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "sampling-and-counting"]`
tags = ["counting"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/ApproxMC.jpg"
#caption = "My caption :smile:"

code_link = "https://github.com/meelgroup/ganak"

+++

Given a Boolean formula $F$, the problem of  model counting, also referred to as #SAT, seeks to compute the number of solutions of $F$. Model counting is a fundamental problem with a wide variety of applications ranging from planning, quantified information flow to probabilistic reasoning and the like. The modern #SAT solvers tend to be either based on static decomposition, dynamic decomposition, or a hybrid of the two. Despite dynamic decomposition based #SAT solvers sharing much of their architecture with SAT solvers, the core design and heuristics of dynamic decomposition-based #SAT solvers has remained constant for over a decade. In this paper, we revisit the architecture of the state-of-the-art dynamic decomposition-based #SAT tool, sharpSAT, and demonstrate that by introducing a new notion of probabilistic component caching and the usage of universal hashing for exact model counting along with the development of several new heuristics can lead to significant performance improvement over state-of-the-art model-counters. In particular, we develop GANAK, a new scalable probabilistic exact model counter that outperforms state-of-the-art exact and approximate model counters sharpSAT and ApproxMC3 respectively, both in terms of PAR-2 score and the number of instances solved. Furthermore, in our experiments, the model count returned by GANAK was equal to the exact model count for all the benchmarks. Finally, we observe that recently proposed preprocessing techniques for model counting benefit exact model counters while hurting the performance of approximate model counters.

**Relevant Papers:**

* [IJCAI 2019](https://www.comp.nus.edu.sg/~meel/Papers/ijcai19srsm.pdf "IJCAI 2019")
