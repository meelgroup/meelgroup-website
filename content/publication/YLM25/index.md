---
title: On Top-Down Pseudo-Boolean Model Counting
authors:
- Suwei Yang
- Yong Lai
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT)*
publication_types:
- '1'
featured: false
math: true
abstract: Pseudo-Boolean model counting involves computing the number of satisfying assignments of a given pseudo-Boolean (PB) formula. In recent years, PB model counting has seen increased interest partly owing to the succinctness of PB formulas over typical propositional Boolean formulas in conjunctive normal form (CNF) at describing problem constraints. In particular, the research community has developed tools to tackle exact PB model counting. These recently developed counters follow one of the two existing major designs for model counters, namely the bottom-up model counter design. A natural question would be whether the other major design, the top-down model counter paradigm, would be effective at PB model counting, especially when the top-down design offered superior performance in CNF model counting literature. In this work, we investigate the aforementioned top-down design for PB model counting and introduce the first exact top-down PB model counter, PBMC. PBMC is a top-down search-based
  counter for PB formulas, with a new variable decision heuristic that considers variable coefficients. Through our evaluations, we highlight the superior performance of PBMC at PB model counting compared to the existing state-of-the-art counters PBCount, PBCounter, and Ganak. In particular, PBMC could count for 1849 instances while the next-best competing method, PBCount, could only count for 1773 instances, demonstrating the potential of a top-down PB counter design.
url_pdf: https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.SAT.2025.31
tags:
- Counting
---
