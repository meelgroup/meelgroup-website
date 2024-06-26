---
abstract: Given a CNF formula and a weight for each assignment of values to variables,
  two natural problems are weighted model counting and distribution-aware sampling
  of satisfying assignments. Both problems have a wide variety of important applications.
  Due to the inherent complexity of the exact versions of the problems, interest has
  focused on solving them approximately. Prior work in this area scaled only to small
  problems in practice, or failed to provide strong theoretical guarantees, or employed
  a computationally-expensive maximum a posteriori probability (MAP) oracle that assumes
  prior knowledge of a factored representation of the weight distribution. We present
  a novel approach that works with a black-box oracle for weights of assignments and
  requires only an {NP}-oracle (in practice, a SAT-solver) to solve both the counting
  and sampling problems. Our approach works under mild assumptions on the distribution
  of weights of satisfying assignments, provides strong theoretical guarantees, and
  scales to problems involving several thousand variables. We also show that the assumptions
  can be significantly relaxed while improving computational efficiency if a factored
  representation of the weights is known.
authors:
- Supratik Chakraborty
- Daniel J. Fremont
- Kuldeep S. Meel
- Sanjit A. Seshia
- Moshe Y. Vardi
date: 2014-07-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: '*In Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*'
publication_types:
- '1'
selected: true
title: Distribution-Aware Sampling and Weighted Model Counting for SAT
url_code: https://bitbucket.org/kuldeepmeel/weightmc/src/master/
url_pdf: https://www.cs.toronto.edu/~meel/Papers/AAAI14.pdf
url_slides: files/slides/AAAI-Talk-July 31.pdf
---

