---
abstract: ML algorithms that produce rule-based predictions in Conjunctive Normal
  form (CNF) or in Disjunctive Normal form (DNF) are arguably some of the most interpretable
  ones. Although CNF/DNF rules are considered interpretable in practice, propositional
  logic has other very interpretable representations which are more expressive. In
  this paper, we generalize CNF/DNF rules and introduce relaxed-CNF rules, which is
  motivated by the popular usage of checklists in the medical domain. We consider
  relaxed definitions of standard OR/AND operators which allow exceptions in the construction
  of a clause and also in the selection of clauses in a rule. While the combinatorial
  structure of relaxed-CNF rules offers exponential succinctness, the naive learning
  techniques are computationally expensive. The primary contribution of this paper
  is to propose a novel incremental mini-batch learning procedure, called CRR, that
  employs advances in the combinatorial solvers and efficiently learns relaxed-CNF
  rules. Our experimental analysis demonstrates that CRR can generate relaxed-CNF
  rules which are more accurate compared to CNF rules and sparser compared to decision
  lists.
authors:
- Bishwamittra Ghosh
- Dmitry Malioutov
- Kuldeep S. Meel
date: 2020-01-23 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of ECAI*
publication_types:
- '1'
selected: true
title: Classification Rules in Relaxed Logical Form
url_code: https://github.com/meelgroup/mlic
url_pdf: https://bishwamittra.github.io/publication/ecai_2020/paper.pdf
---

