---
title: Engineering an Efficient Approximate DNF-Counter
authors:
- Mate Soos
- Divesh Aggarwal
- Sourav Chakraborty
- Kuldeep S. Meel
- Maciej Obremski
date: '2023-01-01T00:00:00'
publication: In *Proceedings of International Joint Conference on Artificial Intelligence (IJCAI)*
publication_types:
- '1'
featured: false
math: true
abstract: 'Model counting is a fundamental problem with many practical applications, including query evaluation in probabilistic databases and failure-probability estimation of networks. In this work, we focus on a variant of this problem where the underlying formula is expressed in Disjunctive Normal Form (DNF), also known as #DNF. This problem has been shown to be #P-complete, making it intractable to solve exactly. Much research has therefore been focused on obtaining approximate solutions, particularly in the form of (ϵ, δ) approximations. The primary contribution of this paper is a new approach, called dnfstream, to approximate #DNF counting that achieves (nearly) optimal time complexity and outperforms existing FPRAS. Our approach is based on the recent breakthrough in the context of union of sets in streaming. We demonstrate the effectiveness of our approach through extensive experiments and show that it provides an affirmative answer to the challenge of efficiently computing #DNF.'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/ijcai23-sacmo.pdf
tags:
- Counting
---
