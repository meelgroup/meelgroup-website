---
abstract: ' Given epsilon and a Boolean formula F, the problem of almost-uniform generation seeks to generate solutions such that every solution is generated with a probability that is within (1+epsilon)-multiplicative factor of 1/#F where #F is the number of solutions of F. The problem of almost-uniform generation was shown to be inter-reducible to that of randomized approximate counting in the seminal work of Jerrum, Valiant, and Vazirani (TCS, 1986). The proposed reduction, however, requires a linear number of calls to approximate counter, and therefore, provides an O(n log (n) log (n/epsilon)) algorithm that employs pairwise independent hash functions. In this work, we propose a new algorithm that makes only one call to the approximate counter, and in turn, provides an O( log n * log (1/epsilon) + 1/epsilon) algorithm for an almost-uniform generation. The key ingredient of our approach is a beautiful combination of the usage of approximate counting and 3-wise independent hash functions. Since the standard tabulation-based hash family proposed by Carter and Wegman (STOC 1977) is known to be 3-wise independent, our scheme can be highly efficient in practical applications where a SAT solver is typically used in lieu of a NP oracle. We demonstrate that theoretical improvements translate to practice; in particular, we conduct a comprehensive study over 562 benchmarks and demonstrate that while JVV would time out for 544 out of 562 instances, our proposed scheme can handle all the 562 instances. To the best of our knowledge, this is the first almost-uniform generation scheme that can handle practical instances from real-world applications. We also present a nuanced analysis focusing on the both the size of SAT queries as well as the number of queries.'
authors:
- " Remi Delannoy and Kuldeep S. Meel "
date: 2022-06-23 00:00:01
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Logic in Computer science (LICS)*
publication_types:
- '1'
selected: true
title: 'On Almost-Uniform Generation of SAT Solutions: The power of 3-wise independent hashing'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/lics22.pdf
---

