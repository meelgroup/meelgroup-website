---
abstract: "Given a set of constraints F and a weight function W over the assignments, the problem of MaxSAT is to compute a maximum weighted solution of F. MaxSAT is a fundamental problem with applications in numerous areas. The success of MaxSAT solvers has prompted researchers in AI and formal methods communities to develop algorithms that can use MaxSAT solver as oracle. One such problem that stands to benefit from advances in MaxSAT solving is discrete integration. Recently, Ermon et al. achieved a significant breakthrough by reducing the problem of integration to polynomially many queries to an optimization oracle where F is conjuncted with randomly chosen XOR constraints.
The primary contribution of this paper is a new MaxSAT solver, GaussMaxHS, with built-in XOR support. The architecture of GaussMaxHS is inspired by CryptoMiniSat, which has been the workhorse of hashing-based approximate model counting techniques. Our solver, GaussMaxHS, outperforms MaxHS over 9628 benchmarks arising from spin glass models and network reliability domains. In particular, with a timeout of 5000 seconds, MaxHS could solve only 5473 benchmarks while GaussMaxHS could solve 6120 benchmarks."
authors:
- Mate Soos
- Kuldeep S. Meel
date: 2021-11-09 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Principles of Knowledge Representation and Reasoning (KR)*
publication_types:
- '1'
selected: true
title: 'Gaussian Elimination Meets Maximum Satisfiability'
url_pdf: https://proceedings.kr.org/2021/55/kr2021-0055-soos-et-al.pdf
# url_dataset: https://doi.org/10.5281/zenodo.5526835
url_code: https://github.com/meelgroup/gaussmaxhs
url_poster: files/slides/KR21_poster.pdf
# url_video: https://www.youtube.com/watch?v=vCc6jpOm04Y&feature=youtu.be
---

