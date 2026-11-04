---
title: Improved Streaming Algorithm for the Klee's Measure Problem and Generalizations
authors:
- Mridul Nandi
- N. V. Vinodchandran
- Arijit Ghosh
- Kuldeep S. Meel
- Soumit Pal
- Sourav Chakraborty
date: '2024-01-01T00:00:00'
publication: In *Proceedings of the International Conference on Approximation Algorithms for Combinatorial Optimization Problems (APPROX)*
publication_types:
- '1'
featured: false
math: true
abstract: Estimating the size of the union of a stream of sets S_1, S_2, … S_M where each set is a subset of a known universe Ω is a fundamental problem in data streaming. This problem naturally generalizes the well-studied estimation problem in the streaming literature, where each set contains a single element from the universe. We consider the general case when the sets S_i can be succinctly represented and allow efficient membership, cardinality, and sampling queries (called a Delphic family of sets). A notable example in this framework is the Klee's Measure Problem (KMP), where every set S_i is an axis-parallel rectangle in d-dimensional spaces (Ω = [Δ]^d where [Δ] := {1, …, Δ} and Δ∈ℕ). Recently, Meel, Chakraborty, and Vinodchandran (PODS-21, PODS-22) designed a streaming algorithm for (ϵ,δ)-estimation of the size of the union of set streams over Delphic family with space and update time complexity O(log^3 |Ω|/ε^2·log1/δ) and O(log^4 |Ω|/ε^2·log1/δ), respectively. This work presents
  a new, sampling-based algorithm for estimating the size of the union of Delphic sets that has space and update time complexity O(log^2 |Ω|/ε^2·log1/δ). This improves the space complexity bound by a log|Ω| factor and update time complexity bound by a log^2 |Ω| factor. A critical question is whether quadratic dependence of log |Ω| on space and update time complexities is necessary. Specifically, can we design a streaming algorithm for estimating the size of the union of sets over Delphic family with space and complexity linear in log |Ω| and update time (log |Ω|)? While this appears technically challenging, we show that establishing a lower bound of ω(log |Ω|) with (log |Ω|) update time is beyond the reach of current techniques. Specifically, we show that under certain hard-to-prove computational complexity hypothesis, there is a streaming algorithm for the problem with optimal space complexity O(log |Ω|) update time (log(|Ω|)). Thus, establishing a space lower bound of ω(log |Ω|) will lead
  to break-through complexity class separation results.
tags:
- Data Streams
---
