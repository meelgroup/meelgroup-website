---
abstract: 'Given a universe $\Omega$, estimating the size of the union of sets S_1, S_2,... S_M in a streaming model is a fundamental computational problem with a wide variety of applications. The holy grail in the field of streaming is to seek design of algorithms that achieve $(\varepsilon, \delta)$-approximation with $\poly(\log |\Omega|, \varepsilon^{-1}, \log \delta^{-1})$ space and update time complexity. Earlier investigations achieve algorithms with desired space and update time complexity for very restricted cases such as singletons (Distinct Elements problem), one-dimensional ranges, arithmetic progressions, and subcubes. But such techniques fail for many other simple structured sets. A prominent example is that of Klee''s Measure Problem (KMP), wherein every set $S_i$ is represented by an axis parallel rectangles in $d$-dimensional spaces. Despite an extensive prior work, the best known streaming algorithms for many of these cases, depend on the size of stream, and therefore the problem of whether there exists streaming algorithm for estimations of size of union of sets with $\poly(\log |\Omega|, \varepsilon^{-1}, \log \delta^{-1})$ space and update time complexity has remained open. In this work, we focus on the general family called Delphic sets (which allows {\em efficient} membership, sampling, and cardinality queries) and which captures several well-known problems including KMP, test coverage, and hypervolume estimation. The primary contribution of our work is to resolve the above-mentioned long standing open problem for Delphic sets. In particular, we design the first streaming algorithm for estimation of $\left |\bigcup_{i=1}^{M} S_i\right |$ with $\poly(\log |\Omega|,$ $ \varepsilon^{-1}, \log \delta^{-1})$ space and update time complexity (independent of the $M$, the length of the stream) when each $S_i$ is a Delphic set. We further generalize our results to a larger family, called {\em approximate Delphic}, for which the size of a set can be known approximately but not exactly, thereby resolving two of the open problems of Meel, Vinodchandran, Chakraborty (PODS-21).}'
authors:
- Kuldeep Meel
- Sourav Chakraborty
- N.V. Vinodchandran
date: 2022-06-22 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *ACM Symposium on Principles of Database Systems (PODS)*
publication_types:
- '1'
selected: true
title: 'Estimation of the Size of Union of Delphic Sets: Achieving Independence from Stream Size'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/pods22.pdf
---
