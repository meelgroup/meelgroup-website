---
title: CNFs and DNFs with Exactly k Solutions
authors:
- L. Sunil Chandran
- Rishikesh Gajjala
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT)*
publication_types:
- '1'
featured: false
math: true
abstract: 'Model counting is a fundamental problem that consists of determining the number of satisfying assignments for a given Boolean formula. The weighted variant, which computes the weighted sum of satisfying assignments, has extensive applications in probabilistic reasoning, network reliability, statistical physics, and formal verification. A common approach for solving weighted model counting is to reduce it to unweighted model counting, which raises an important question: What is the minimum number of terms (or clauses) required to construct a DNF (or CNF) formula with exactly k satisfying assignments? In this paper, we establish both upper and lower bounds on this question. We prove that for any natural number k, one can construct a monotone DNF formula with exactly k satisfying assignments using at most O(sqrtlog klog log k) terms. This construction represents the first o(log k) upper bound for this problem. We complement this result by showing that there exist infinitely many
  values of k for which any DNF or CNF representation requires at least Omega(log log k) terms or clauses. These results have significant implications for the efficiency of model counting algorithms based on formula transformations.'
url_pdf: https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.SAT.2025.9
tags:
- Counting
---
