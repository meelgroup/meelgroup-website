---
title: 'Arjun: An Efficient Independent Support Computation Technique and its Applications to Counting and Sampling'
authors:
- Mate Soos
- Kuldeep S. Meel
date: '2022-01-01T00:00:00'
publication: In *Proceedings of IEEE/ACM International Conference on Computer-Aided Design (ICCAD)*
publication_types:
- '1'
featured: false
math: true
abstract: Given a Boolean formula F over the set of variables X and a projection set P, a subset of variables I is independent support of P if two solutions agree on I, then they also agree on P. The notion of independent support is related to the classical notion of definability dating back to 1901, and have been studied over the decades. Recently, the computational problem of determining independent support for a given formula has attained importance owing to the crucial importance of independent support for hashing-based counting and sampling techniques. In this paper, we design an efficient and scalable independent support computation technique that can handle formulas arising from real-world benchmarks. Our algorithmic framework, called Arjun, employs implicit and explicit definability notions, and is based on a tight integration of gate-identification techniques and assumption-based framework. We demonstrate that augmenting the state of the art model counter ApproxMC4 and sampler UniGen3
  with Arjun leads to significant performance improvements. In particular, ApproxMC4 augmented with Arjun counts 387 more benchmarks out of 1896 while UniGen3 augmented with Arjun samples 319 more benchmarks within the same time limit.
url_pdf: https://www.cs.toronto.edu/~meel/Papers/iccad22.pdf
tags:
- Counting
- Sampling
- Solver Engineering
---
