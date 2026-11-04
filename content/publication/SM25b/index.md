---
title: Approximate SMT Counting Beyond Discrete Domains
authors:
- Arijit Shaw
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of Design Automation Conference (DAC)*
publication_types:
- '1'
featured: false
math: true
abstract: Satisfiability Modulo Theory (SMT) solvers have advanced automated reasoning, solving complex formulas across discrete and continuous domains. Recent progress in propositional model counting motivates extending SMT capabilities toward model counting, especially for hybrid SMT formulas. Existing approaches, like bit-blasting, are limited to discrete variables, highlighting the challenge of counting solutions projected onto the discrete domain in hybrid formulas. We introduce pact, an SMT model counter for hybrid formulas that uses hashing-based approximate model counting to estimate solutions with theoretical guarantees. pact makes a logarithmic number of SMT solver calls relative to the projection variables, leveraging optimized hash functions. pact achieves significant performance improvements over baselines on a large suite of benchmarks. In particular, out of 3119 instances, pact successfully finished on 456 instances, while Baseline could finish on 83 instances.
url_pdf: https://arxiv.org/pdf/2507.18612
tags:
- Counting
---
