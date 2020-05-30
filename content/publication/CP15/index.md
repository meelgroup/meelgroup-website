---
abstract: Constrained sampling and counting are two fundamental problems arising in
  domains ranging from artificial intelligence and security, to hardware and software
  testing. Recent approaches to approximate solutions for these problems rely on employing
  SAT solvers and universal hash functions that are typically encoded as XOR constraints
  of length n/2 for an input formula with n variables. As the runtime performance
  of SAT solvers heavily depends on the length of XOR constraints, recent research
  effort has been focused on reduction of length of XOR constraints. Consequently,
  a notion of Independent Support was proposed, and it was shown that constructing
  XORs over independent support (if known) can lead to a significant reduction in
  the length of XOR constraints without losing the theoretical guarantees of sampling
  and counting algorithms. In this paper, we present the first algorithmic procedure
  (and a corresponding tool, called MIS) to determine minimal independent support
  for a given CNF formula by employing a reduction to group minimal unsatisfiable
  subsets (GMUS). By utilizing minimal independent supports computed by MIS, we provide
  new tighter bounds on the length of XOR constraints for constrained counting and
  sampling. Furthermore, the universal hash functions constructed from independent
  supports computed by MIS provide two to three orders of magnitude performance improvement
  in state-of-the-art constrained sampling and counting tools, while still retaining
  theoretical guarantees.
authors:
- Alexander Ivrii
- Sharad Malik
- Kuldeep S. Meel
- Moshe Y. Vardi
date: 2015-09-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming
  (CP)*
publication_types:
- '1'
selected: true
title: 'On Computing Minimal Independent Support and Its Applications to Sampling
  and Counting '
url_code: https://bitbucket.org/kuldeepmeel/mis/src/master/
url_pdf: http://www.comp.nus.edu.sg/~meel/Papers/constraints.pdf
url_slides: files/slides/KSM CP15Talk.pdf
---

