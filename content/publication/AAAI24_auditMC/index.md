---
abstract: "Model counting, or counting the satisfying assignments of a Boolean formula, is a fundamental problem with diverse applications.  Given #P-hardness of the problem, developing algorithms for approximate counting is an important research area. Building on the practical success of SAT-solvers, the focus has recently shifted from theory to practical implementations of approximate counting algorithms. This has brought to focus new challenges, such as the design of auditable approximate counters that not only provide an approximation of themodel count, but also a certificate that a verifier with limited computational power can use to check if the count is indeed within the
promised bounds of approximation.

Towards generating certificates, we start by examining the best-known deterministic approximate counting algorithm that uses polynomially many calls to a $\\Sigma_2^P$ oracle. We show that this can be audited via a $\\Sigma_2^P$ oracle with the query constructed over $n^2 \\log^2 n$ variables, where the original formula has $n$ variables.  Since $n$ is often large, we ask if the count of variables in the certificate can be reduced -- a crucial question for potential implementation. We show that this is indeed possible with a tradeoff in the counting algorithm's complexity. Specifically, we develop new deterministic approximate counting algorithms that invoke a $\\Sigma_3^P$ oracle, but can be certified using a $\\Sigma_2^P$ oracle using certificates on far fewer variables: our final algorithm uses only $n \\log n$ variables. 
Our study demonstrates that one can simplify auditing significantly if we allow the counting algorithm to access a slightly more powerful oracle. This shows for the first time how audit complexity can be traded for complexity of approximate counting."


authors:
- Kuldeep S. Meel
- Supratik Chakraborty
- S. Akshay
date: 2024-02-21 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the AAAI Conference on Artificial Intelligenc (AAAI)*
publication_types:
- '1'
selected: true
title: 'Auditable Algorithms for Approximate Model Counting'
url_pdf: 'https://arxiv.org/pdf/2312.12362.pdf'
---
