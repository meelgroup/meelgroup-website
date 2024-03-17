---
abstract: "Samplers are the backbone of the implementations of any randomised algorithm. Unfortunately, obtaining an efficient algorithm to test the correctness of samplers is very hard to find. Recently, in a series of works, testers like 𝖡𝖺𝗋𝖻𝖺𝗋𝗂𝗄, 𝖳𝖾𝗊, 𝖥𝗅𝖺𝗌𝗁 for testing of some particular kinds of samplers, like CNF-samplers and Horn-samplers, were obtained. But their techniques have a significant limitation because one can not expect to use their methods to test for other samplers, such as perfect matching samplers or samplers for sampling linear extensions in posets. In this paper, we present a new testing algorithm that works for such samplers and can estimate the distance of a new sampler from a known sampler (say, uniform sampler). Testing the identity of distributions is the heart of testing the correctness of samplers. This paper's main technical contribution is developing a new distance estimation algorithm for distributions over high-dimensional cubes using the recently proposed sub-cube conditioning sampling model. Given subcube conditioning access to an unknown distribution $P$, and a known distribution $Q$ defined over ${0,1}^n$, our algorithm 𝖢𝗎𝖻𝖾𝖯𝗋𝗈𝖻𝖾𝖤𝗌𝗍 estimates the variation distance between $P$ and $Q$ within additive error $\zeta$ using $O(n^2/\zeta^4)$ subcube conditional samples from $P$. Following the testing-via-learning paradigm, we also get a tester which distinguishes between the cases when $P$ and $Q$ are $\varepsilon$-close or $\eta$-far in variation distance with probability at least 0.99 using $O(n^2/(\eta−\varepsilon)^4)$ subcube conditional samples. The estimation algorithm in the sub-cube conditioning sampling model helps us to design the first tester for self-reducible samplers."


authors:
- Rishiraj Bhattacharya
- Sourav Chakraborty
- Yash Pote
- Uddalok Sarkar
- Sayantan Sen
date: 2023-12-21 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the AAAI Conference on Artificial Intelligenc (AAAI)*
publication_types:
- '1'
selected: true
title: 'Testing Self-Reducible Samplers'
---
