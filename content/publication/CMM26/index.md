---
title: Counting and Sampling Traces in Regular Languages
authors:
- Alexis de Colnet
- Kuldeep S. Meel
- Umang Mathur
date: '2026-01-01T00:00:00'
publication: '*Proceedings of the ACM on Programming Languages*, 10(POPL), pp. 2352–2379'
publication_types:
- '2'
featured: false
math: true
abstract: 'In this work, we study the fundamental problems of counting and sampling traces that a regular language touches. Formally, one fixes the alphabet Sigma and an independence relation I subseteq Sigma x Sigma. The computational problems we address take as input a regular language L over Sigma, presented as a finite automaton with m states, together with a natural number n (presented in unary). For the counting problem, the output is the number of Mazurkiewicz traces (induced by I) that intersect the n th slice L n = L cap Sigma n of L , i.e., traces that have at least one linearization in L n . For the sampling problem, the output is a trace drawn from a distribution that is approximately uniform over all such traces. These problems are motivated by applications such as bounded model checking based on partial-order reduction, where an a priori estimate of the size of the state space can significantly improve usability, as well as testing approaches for concurrent programs that use
  partial-order-aware random sampling, where uniform exploration is desirable for effective bug detection. We first show that the counting problem is #P-hard even when the automaton accepting the language L is deterministic, which is in sharp contrast to the corresponding problem for counting the words of a DFA, which is solvable in polynomial time. We then show that the counting problem remains in the class #P for both NFAs and DFAs, independent of whether L is trace-closed. Finally, our main contributions are a fully polynomial-time randomized approximation scheme (FPRAS) that, with high probability, estimates the desired count within a specified accuracy parameter, and a fully polynomial-time almost uniform sampler (FPAUS) that generates traces while ensuring that the distribution induced on them is approximately uniform with high probability.'
doi: 10.1145/3776723
tags:
- Counting
- Sampling
volume: '10'
number: POPL
pages: 2352--2379
---
