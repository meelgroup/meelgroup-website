---
abstract: 'Boolean satisfiability is a fundamental problem in computer science with
  a wide range of applications including planning, configuration management, design
  and verification of software/hardware systems. The annual SAT competition continues
  to witness impressive improvements in the performance of the winning SAT solvers
  largely thanks to the development of new heuristics arising out of intensive collaborative
  research in the SAT community. Modern SAT solvers achieve scalability and robustness
  with complex heuristics that are challenging to understand and explain. Consequently,
  the development of new algorithmic insights has been largely restricted to expert
  intuitions and evaluation of the new insights have been restricted to performance
  measurement in terms of the runtime of solvers or a proxy for the runtime of solvers.
  In this context, one may ask: whether it is possible to develop a framework to provide
  white-box access to the execution of SAT solver that can aid both SAT solver developers
  and users to synthesize algorithmic heuristics for modern SAT solvers? The primary
  focus of our project is precisely such a framework, which we call CrystalBall More
  precisely, we propose to view modern conflict-driven clause learning (CDCL) solvers
  as a composition of classifiers and regressors for different tasks such as branching,
  clause memory management, and restarting. The primary objective of this paper is
  to introduce a framework to peek inside the SAT solvers -- CrystalBall -- to the
  AI and SAT community. The current version of CrystalBall focuses on deriving a classifier
  to keep or throw away a learned clause. In a departure from recent machine learning
  based techniques, CrystalBall, employs supervised learning and uses extensive, multi-gigabyte
  data extracted from runs of a single SAT solver to perform predictive analytics. '
authors:
- Mate Soos
- Raghav Kulkarni
- Kuldeep S. Meel
date: 2019-05-05 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications
  of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: 'CrystalBall: Gazing in the Black Box of SAT Solving '
url_code: https://github.com/msoos/cryptominisat/tree/crystalball
url_pdf: https://www.cs.toronto.edu/~meel/Papers/sat19skm.pdf
url_slides: files/slides/Meel-CrystalBall-slides.pdf
---

