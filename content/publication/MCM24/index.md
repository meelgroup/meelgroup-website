---
title: 'A faster FPRAS for #NFA'
authors:
- Kuldeep S. Meel
- Sourav Chakraborty
- Umang Mathur
date: '2024-01-01T00:00:00'
publication: In *Proceedings of ACM Symposium on Principles of Database Systems (PODS)*
publication_types:
- '1'
featured: false
math: true
abstract: 'Given a non-deterministic finite automaton (NFA) A with m states, and a natural number n (presented in unary), the #NFA problem asks to determine the size of the set L(A_n) of words of length n accepted by A. While the corresponding decision problem of checking the emptiness of L(A_n) is solvable in polynomial time, the #NFA problem is known to be #P-hard. Recently, the long-standing open question – whether there is an FPRAS (fully polynomial time randomized approximation scheme) for #NFA – was resolved in <cit.>. The FPRAS due to [ACJR19] relies on the interreducibility of counting and sampling, and computes, for each pair of state q and natural number i <= n, a set of O(m^7 n^7/epsilon^7) many uniformly chosen samples from the set of words of length i that have a run ending at q (ϵis the error tolerance parameter of the FPRAS). This informative measure – the number of samples maintained per state and length – also affects the overall time complexity with a quadratic dependence.
  Given the prohibitively high time complexity, in terms of each of the input parameters, of the FPRAS due to [ACJR19], and considering the widespread application of approximate counting (and sampling) in various tasks in Computer Science, a natural question arises: Is there a faster FPRAS for #NFA that can pave the way for the practical implementation of approximate #NFA tools? In this work, we demonstrate that significant improvements in time complexity are achievable. Specifically, we have reduced the number of samples required for each state to be independent of m, with significantly less dependence on n and epsilon, maintaining only O(n^4/epsilon^2) samples per state.'
url_pdf: https://arxiv.org/abs/2312.13320
tags:
- Counting
---
