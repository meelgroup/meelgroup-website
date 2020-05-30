---
abstract: 'Given a Boolean formula $F$, the problem of  model counting, also referred
  to as #SAT, seeks to compute the number of solutions of $F$. Model counting is a
  fundamental problem with a wide variety of applications ranging from planning, quantified
  information flow to probabilistic reasoning and the like. The modern #SAT solvers
  tend to be either based on static decomposition, dynamic decomposition, or a hybrid
  of the two. Despite dynamic decomposition based #SAT solvers sharing much of their
  architecture with SAT solvers, the core design and heuristics of dynamic decomposition-based
  #SAT solvers has remained constant for over a decade. In this paper, we revisit
  the architecture of the state-of-the-art dynamic decomposition-based #SAT tool,
  sharpSAT, and demonstrate that by introducing a new notion of probabilistic component
  caching and the usage of universal hashing for exact model counting along with the
  development of several new heuristics can lead to significant performance improvement
  over state-of-the-art model-counters. In particular, we develop GANAK, a new scalable
  probabilistic exact model counter that outperforms state-of-the-art exact and approximate
  model counters sharpSAT and ApproxMC3 respectively, both in terms of PAR-2 score
  and the number of instances solved. Furthermore, in our experiments, the model count
  returned by GANAK was equal to the exact model count for all the benchmarks. Finally,
  we observe that recently proposed preprocessing techniques for model counting benefit
  exact model counters while hurting the performance of approximate model counters.'
authors:
- Shubham Sharma
- Subhajit Roy
- Mate Soos
- Kuldeep S. Meel
date: 2019-05-21 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings International Joint Conference on Artificial Intelligence
  (IJCAI)*
publication_types:
- '1'
selected: true
title: 'GANAK: A Scalable Probabilistic Exact Model Counter'
url_code: https://github.com/meelgroup/ganak
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/ijcai19srsm.pdf
url_slides: files/slides/ganak_ijcai_pres.pdf
---

