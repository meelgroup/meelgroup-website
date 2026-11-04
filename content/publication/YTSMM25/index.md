---
title: Efficient Certified Reasoning for Binarized Neural Networks
authors:
- Jiong Yang
- Yong Kiam Tan
- Mate Soos
- Magnus O. Myreen
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT)*
publication_types:
- '1'
featured: false
math: true
abstract: Neural networks have emerged as essential components in safety-critical applications - these use cases demand complex, yet trustworthy computations. Binarized Neural Networks (BNNs) are a type of neural network where each neuron is constrained to a Boolean value; they are particularly well-suited for safety-critical tasks because they retain much of the computational capacities of full-scale (floating-point or quantized) deep neural networks, but remain compatible with satisfiability solvers for qualitative verification and with model counters for quantitative reasoning. However, existing methods for BNN analysis suffer from either limited scalability or susceptibility to soundness errors, which hinders their applicability in real-world scenarios. In this work, we present a scalable and trustworthy approach for both qualitative and quantitative verification of BNNs. Our approach introduces a native representation of BNN constraints in a custom-designed solver for qualitative reasoning,
  and in an approximate model counter for quantitative reasoning. We further develop specialized proof generation and checking pipelines with native support for BNN constraint reasoning, ensuring trustworthiness for all of our verification results. Empirical evaluations on a BNN robustness verification benchmark suite demonstrate that our certified solving approach achieves a 9x speedup over prior certified CNF and PB-based approaches, and our certified counting approach achieves a 218x speedup over the existing CNF-based baseline. In terms of coverage, our pipeline produces fully certified results for 99% and 86% of the qualitative and quantitative reasoning queries on BNNs, respectively. This is in sharp contrast to the best existing baselines which can fully certify only 62% and 4% of the queries, respectively.
url_pdf: https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.SAT.2025.32
tags:
- Formal Methods 4 ML
---
