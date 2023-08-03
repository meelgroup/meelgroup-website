---
authors:
- Davin Choo
- ' Mate Soos'
- Kian Ming A. Chai
- Kuldeep S. Meel
date: 2019-02-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Design, Automation, and Test in Europe (DATE)*
publication_types:
- '1'
selected: true
title: 'BOSPHORUS: Bridging ANF and CNF Solvers '
url_code: https://github.com/meelgroup/bosphorus
url_pdf: https://www.cs.toronto.edu/~meel/Papers/date-cscm19.pdf
---
Algebraic Normal Form (ANF) and Conjunctive Normal Form (CNF) are commonly used to encode problems in Boolean algebra. ANFs are typically solved via Gröbner basis algorithms, often using more memory than is feasible; while CNFs are solved using SAT solvers, which cannot exploit the algebra of polynomials naturally. We propose a paradigm that bridges between ANF and CNF solving techniques: the techniques are applied in an iterative manner to learn facts to augment the original problems. Experiments on over 1,100 benchmarks arising from four different applications domains demonstrate that learnt facts can significantly improve runtime and enable more benchmarks to be solved.
