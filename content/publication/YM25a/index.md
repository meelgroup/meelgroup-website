---
title: Rounding meets approximate model counting
authors:
- Jiong Yang
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: '*Formal Methods in System Design*'
publication_types:
- '2'
featured: false
math: true
doi: 10.1007/s10703-025-00481-6
tags:
- Counting
abstract: 'The problem of model counting, also known as # # SAT , is to compute the number of models or satisfying assignments of a given Boolean formula F . Model counting is a fundamental problem in computer science with a wide range of applications. In recent years, there has been a growing interest in using hashing-based techniques for approximate model counting that provide (ε , δ ) ( epsilon , delta ) -guarantees: i.e., the count returned is within a (1+ε ) ( 1 + epsilon ) -factor of the exact count with confidence at least 1-δ 1 - delta . While hashing-based techniques attain reasonable scalability for large enough values of δ delta , their scalability is severely impacted for smaller values of δ delta , thereby preventing their adoption in application domains that require estimates with high confidence. The primary contribution of this paper is to address the Achilles heel of hashing-based techniques: we propose a novel approach based on rounding that allows us to achieve a significant
  reduction in runtime for smaller values of δ delta . The resulting counter, called ApproxMC 6 , achieves a substantial runtime performance improvement over the current state-of-the-art counter, ApproxMC . In particular, our extensive evaluation over a benchmark suite consisting of 1890 instances shows ApproxMC 6 solves 204 more instances than ApproxMC , and achieves a 4× 4 x speedup over ApproxMC .'
---
