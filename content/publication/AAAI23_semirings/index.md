---
abstract: 'The interpretation of logical formulas over semirings, which provide more information than simply the truth or falsity of a statement, have applications in computer science fields such as AI, databases, security, and logic. These semirings include the Viterbi semiring, the min-max or access control semiring, the tropical semiring, and the fuzzy semiring. This work explores the complexity of constraint optimization problems over semirings. The generic optimization problem studied is: given a propositional formula $\varphi$ over $n$ variables and a semiring $(K, +, \cdot, 0, 1)$, find the maximum value of all possible interpretations of $\varphi$ over $K$. This can be seen as a generalization of the well-known satisfiability problem, where a propositional formula is satisfiable if and only if the maximum value over all interpretations/assignments over the Boolean semiring is 1. A related problem is to find an interpretation that achieves the maximum value. This work focuses on these optimization problems over the Viterbi semiring, which are called optConfVal and optConf. It is shown that for general propositional formulas in negation normal form, optConfVal and optConf are in FPNP. When the input formula $\varphi$ is represented in conjunctive normal form, the complexity of optConf is investigated. For CNF formulae, an upper bound on the value of optConf as a function of the number of maximum satisfiable clauses is derived. It is shown that if $r$ is the maximum number of satisfiable clauses in a CNF formula with $m$ clauses, then its optConf value is at most $\frac14m-r$. Based on this result, it is established that optConf for CNF formulae is hard for the complexity class FPNP[log]. Polynomial-time approximation algorithms are also designed, and the inapproximability of optConfVal is established. Similar complexity results for these optimization problems over other semirings, such as the tropical, fuzzy, and access control semirings, are also established.'
authors:
- A. Pavan
- Kuldeep S. Meel
- N. V. Vinodchandran
- Arnab Bhattacharyya
date: 2023-01-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the 37th AAAI Conference on Artificial Intelligence (AAAI23)*
publication_types:
- '1'
selected: true
title: 'Constraint Optimization over Semirings'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/aaai23-pmvb.pdf
---

