---
abstract: "One approach to probabilistic inference involves counting the number of models of a given Boolean formula. Here, we are interested in inferences involving higher-order objects, i.e., functions. We study the following task: Given a Boolean specification between a set of inputs and outputs, count the number of functions of inputs such that the specification is met. Such functions are called Skolem functions.

We are motivated by the recent development of scalable approaches to Boolean function synthesis. This stands in relation to our problem analogously to the relationship between Boolean satisfiability and the model counting problem. Yet, counting Skolem functions poses considerable new challenges. From the complexity-theoretic standpoint, counting Skolem functions is not only $\#P$-hard; it is quite unlikely to have an FPRAS (Fully Polynomial Randomized Approximation
Scheme) as the problem of synthesizing a Skolem function remains challenging, even given access to an NP oracle.

The primary contribution of this work is the first algorithm, SkolemFC, that computes an estimate of the number of Skolem functions. SkolemFC relies on technical connections between counting functions and propositional model counting: our algorithm makes a linear number of calls to an approximate model counter and computes an estimate of the number of Skolem functions with theoretical guarantees. Moreover, we show that Skolem function count can be approximated through a polynomial number of calls to a SAT oracle. Our prototype displays impressive scalability, handling benchmarks comparably to state-of-the-art Skolem function synthesis engines, even though counting all such functions ostensibly poses a greater challenge than synthesizing a single function.
"

authors:
- Arijit Shaw  
- Brendan Juba
- Kuldeep S. Meel
date: 2023-12-21 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'An Approximate Skolem Function Counter'
---