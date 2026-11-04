---
title: 'Towards Practical FPRAS for #NFA: Exploiting the Power of Dependence'
authors:
- Kuldeep S. Meel
- Alexis de Colnet
date: '2025-01-01T00:00:00'
publication: '*Proceedings of the ACM on Management of Data*'
publication_types:
- '2'
featured: false
math: true
abstract: '#NFA refers to the problem of counting the words of length n accepted by a non-deterministic finite automaton. #NFA is #P-hard, and although fully-polynomial-time randomized approximation schemes (FPRAS) exist, they are all impractical. The first FPRAS for #NFA had a running time of O (n 17 m 17 epsilon -14 log(delta -1 )), where m is the number of states in the automaton, delta in (0,1] is the confidence parameter, and epsilon > 0 is the tolerance parameter (typically smaller than 1). The current best FPRAS achieved a significant improvement in the time complexity relative to the first FPRAS and obtained FPRAS with time complexity O ((n 10 m 2 + n 6 m 3 )epsilon -4 log 2 (delta -1 )). The complexity of the improved FPRAS is still too intimidating to attempt any practical implementation. In this paper, we pursue the quest for practical FPRAS for #NFA by presenting a new algorithm with a time complexity of O(n 2 m 3 log(nm)epsilon -2 log(delta -1 )). Observe that evaluating whether
  a word of length n is accepted by an NFA has a time complexity of O(nm 2 ). Therefore, our proposed FPRAS achieves sub-quadratic complexity with respect to membership checks.'
doi: 10.1145/3725253
tags:
- Counting
---
