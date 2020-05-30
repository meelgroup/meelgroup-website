---
abstract: 'The problem of counting the number of solutions of a DNF formula, also
  called #DNF, is a fundamental problem in artificial intelligence with applications
  in diverse domains ranging from network reliability to probabilistic databases.
  Owing to the intractability of the exact variant, efforts have focused on the design
  of approximate techniques for #DNF. Consequently, several Fully Polynomial Randomized
  Approximation Schemes (FPRASs) based on Monte Carlo techniques have been proposed.
  Recently, it was discovered that hashing-based techniques too lend themselves to
  FPRASs for #DNF. Despite significant improvements, the complexity of the hashing-based
  FPRAS is still worse than that of the best Monte Carlo FPRAS by polylog factors.
  Two questions were left unanswered in previous works: Can the complexity of the
  hashing-based techniques be improved? How do the various approaches stack up against
  each other empirically? In this paper, we first propose a new search procedure for
  the hashing-based FPRAS that removes the polylog factors from its time complexity.
  We then present the first empirical study of runtime behavior of different FPRASs
  for #DNF. The result of our study produces a nuanced picture. First of all, we observe
  that there is no single best algorithm that outperforms all others for all classes
  of formulas and input parameters. Second, we observe that the algorithm with the
  worst time complexity, solves the largest number of benchmarks.'
authors:
- Kuldeep S. Meel
- Aditya A. Shrotri
- Moshe Y. Vardi
date: 2018-08-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming
  (CP)*
publication_types:
- '1'
selected: true
title: 'Not All FPRASs are Equal: Demystifying FPRASs for DNF-Counting '
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/CP2018msv.pdf
url_slides: files/slides/CP2018_MSV_fpras.pdf
---

