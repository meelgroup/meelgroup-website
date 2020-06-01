---
abstract: Propositional model counting is a classic problem that has recently witnessed
  many technical advances and novel applications. While the basic model counting problem
  requires computing the number of all solutions to the given formula, in some important
  application scenarios, the desired count is not of all solutions, but instead, of
  all unique solutions up to isomorphism. In such a scenario, the user herself must
  try to either use the full count that the model counter returns to compute the count
  up to isomorphism, or ensure that the input formula to the model counter adequately
  captures the symmetry breaking predicates so it can directly report the count she
  desires. We study the use of CNF-level and domain-level symmetry breaking predicates
  in the context of the state-of-the-art in model counting, specifically the leading
  approximate model counter ApproxMC and the recently introduced exact model counter
  ProjMC. As benchmarks, we use a range of problems, including structurally complex
  specifications of software systems and constraint satisfaction problems. The results
  show that while it is sometimes feasible to compute the model counts up to isomorphism
  using the full counts that are computed by the model counters, doing so suffers
  from poor scalability. The addition of symmetry breaking predicates substantially
  assists model counters. Domain-specific predicates are particularly useful, and
  in many cases can provide full symmetry breaking to enable highly efficient model
  counting up to isomorphism. We hope our study motivates new research on designing
  model counters that directly account for symmetries to facilitate further applications
  of model counting.
authors:
- Wenxi Wang
- Muhammad Usman
- Alyas Almaawi
- Kaiyuan Wang
- Kuldeep S. Meel
- Sarfraz Khurshid
date: 2020-04-04 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Tools and Algorithms for the Construction and Analysis
  of Systems (TACAS)*
publication_types:
- '1'
selected: true
title: A Study of Symmetry Breaking Predicates and Model Counting
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/tacas20.pdf
---

