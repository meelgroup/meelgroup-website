---
title: Efficient Volume Computation for SMT Formulas
authors:
- Arijit Shaw
- Uddalok Sarkar
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of International Conference on Knowledge Representation and Reasoning (KR)*
publication_types:
- '1'
featured: false
math: true
abstract: Satisfiability Modulo Theory (SMT) has recently emerged as a powerful tool for solving various automated reasoning problems across diverse domains. Unlike traditional satisfiability methods confined to Boolean variables, SMT can reason on real-life variables like bitvectors, integers, and reals. A natural extension in this context is to ask quantitative questions. One such query in the SMT theory of Linear Real Arithmetic (LRA) is computing the volume of the entire satisfiable region defined by SMT formulas. This problem is important in solving different quantitative verification queries in software verification, cyber-physical systems, and neural networks, to mention a few. We introduce ttc, an efficient algorithm that extends the capabilities of SMT solvers to volume computation. Our method decomposes the solution space of SMT Linear Real Arithmetic formulas into a union of overlapping convex polytopes, then computes their volumes and calculates their union. Our algorithm builds
  on recent developments in streaming-mode set unions, volume computation algorithms, and AllSAT techniques. Experimental evaluations demonstrate significant performance improvements over existing state-of-the-art approaches.
doi: 10.24963/kr.2025/53
tags:
- Counting
---
