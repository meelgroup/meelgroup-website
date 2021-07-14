---
abstract: "In this paper we study the problem of estimating the size of the union of sets $S_1, \dots, S_M$ where each set $S_i \subseteq \Omega$ (for some discrete universe $\Omega$) is implicitly presented and comes in a streaming fashion. We define the notion of Delphic sets to capture the class of streaming problems where membership, sampling, and counting calls are efficient. In particular, we show our notion of Delphic sets capture three well-known problems: Klee&apos;s measure, test coverage estimation, and model counting of DNF formulas. The Klee&apos;s measure problem corresponds to computation of volume of multi-dimension axis aligned rectangles, i.e., every $d$-dimension axis-aligned rectangle can be defined as $[a_1,b_1] \times [a_2,b_2] \times \ldots \times [a_d, b_d]$. The problem of test coverage estimation focuses on the computation of coverage measure for a given testing array in the context of combinatorial testing, which is a fundamental technique in the context of hardware and software testing. Finally, given a DNF formula $\varphi = T_1 \vee T_2 \ldots T_m$, the problem of model counting seeks to compute the number of satisfying assignments of $\varphi$. The primary contribution of our work is a simple, elegant, and efficient sampling-based algorithm, called {\hybrid}, for estimation of union in streaming setting. Our algorithm has the worst case space complexity and update time of O((\log |\Omega|) . \frac{(\log M) + \log(\frac{1}{\delta})}{\varepsilon^{2}}). Consequently, our algorithm provides the first algorithm with linear dependence on $d$ for Klee&apos;s measure problem in streaming setting for d>1, thereby settling the open problem of Woodruff and Tirthpura (PODS-12). Furthermore, a straightforward application of our algorithm lends to an efficient algorithm for coverage estimation problem in streaming setting. We then investigate whether the space complexity for coverage estimation can be further improved, and in this context, we present another streaming algorithm that uses near-optimal $O(t\log n/\varepsilon^2)$ space complexity but uses an update algorithm that is in P^NP, thereby showcasing an interesting time vs space trade-off in the streaming setting. Finally, we demonstrate the generality of our Delphic sets by obtaining a streaming algorithm for model counting of DNF formulas. It is worth remarking that we view a key strength of our work is the simplicity of both the algorithm and its theoretical analysis, which makes it amenable to practical implementation and the easy adoption."
authors:
- Kuldeep Meel
- N.V. Vinodchandran
- Sourav Chakraborty
date: 2020-09-18 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *ACM Symposium on Principles of Database Systems (PODS)*
publication_types:
- '1'
selected: true
title: 'Estimating the Size of Unions of Sets in Streaming Models'
#url_pdf:
---

