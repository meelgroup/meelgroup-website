---
title: Engineering an Efficient Probabilistic Exact Model Counter
authors:
- Mate Soos
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of International Conference on Computer-Aided Verification (CAV)*
publication_types:
- '1'
featured: false
math: true
abstract: 'Given a formula F , the problem of model counting, also known as #SAT, is to compute the number of satisfying assignments of F . While model counting has emerged as a crucial primitive in diverse domains from quantitative information flow analysis to neural network verification, scalability remains a fundamental challenge despite advances in both exact and approximate counting techniques. We present Ganak 2 , a novel framework that achieves substantial performance improvements through three key technical innovations: (1) refined residual formula processing incorporating SAT-specific techniques while maintaining seamless state transitions, (2) dual independent set framework maintaining distinct SAT-eligibility and decision sets, and (3) chronological backtracking specifically adapted to model counting. Our empirical evaluation on 1600 previous model counting competition instances demonstrates that Ganak 2 successfully computes counts for 1121 instances within the one hour time
  limit, compared to 1032 instances by the prior state of the art approach, representing an 8.7% improvement. This progress is especially remarkable considering the extensive development and refinement of model counting tools over the years, driven by yearly competitive evaluation in the field.'
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-98682-6_5
tags:
- Counting
- Solver Engineering
---
