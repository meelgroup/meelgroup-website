---
title: Engineering an Efficient Preprocessor for Model Counting
authors:
- Mate Soos
- Kuldeep S. Meel
date: '2024-01-01T00:00:00'
publication: In *Proceedings of Design Automation Conference (DAC)*
publication_types:
- '1'
featured: false
math: true
abstract: 'Given a formula F , the problem of model counting is to computethe number of solutions (also known as models) of F. Over thepast decade, model counting has emerged as key building block ofquantitative reasoning in design automation and artificial intelligence.Given the wide-ranging applications, scalability remains themajor challenge. Motivated by the observation that the formulasimplification can dramatically impact the performance of the stateof-the-art exact model counters, we design a new state-of-the-artpreprocessor, Arjun2, that relies on tight integration of techniques. The design of Arjun2 is motivated from our observation that it is oftenbeneficial to employ preprocessing techniques whose overheadmay be prohibitive for the task of SAT solving but not for modelcounting: accordingly, we rely on a specifically tailored SAT solverdesign for redundancy detection, sampling-boosted backbone detection,as well as storing of redundancy information for the purposesof improving propagation
  within top-down model counters. Our detailed empirical evaluation demonstrates that Arjun2 achieves significant performance improvements over prior model countingpreprocessors in terms of instance-size reductions achieved as wellas the runtime improvements of the downstream model counters.'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/dac24-sm.pdf
tags:
- Counting
- Solver Engineering
---
