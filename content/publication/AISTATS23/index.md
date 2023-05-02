---
abstract: "Sampling over combinatorial spaces is a fundamental problem in artificial intelligence with a wide variety of applications. Since state-of-the-art techniques heavily rely on heuristics whose rigorous analysis remain beyond the reach of current theoretical tools, the past few years have witnessed interest in the design of techniques to test the quality of samplers. The current state-ofthe-art techniques, Barbarik and Barbarik2, focus on the cases where combinatorial spaces are encoded as Conjunctive Normal Form (CNF) formulas. While CNF is a general-purpose form, often techniques rely on exploiting specific representations to achieve speedup. Of particular interest are Horn clauses, which form the basis of the logic programming tools in AI. In this context, a natural question is whether it is possible to design a tester that can determine the correctness of a given Horn sampler. The primary contribution of this paper is an affirmative answer to the above question. We design the first tester, Flash, which tests the correctness of a given Horn sampler: given a specific distribution $\\mathcal{I}$ and parameters $\\eta$, $\\varepsilon$, and $\\delta$ the tester Flash correctly (with probability at least $1 - \\delta$) distinguishes whether the underlying distribution of the Horn-sampler is “$\\varepsilon$-close” to $\\mathcal{I}$ or “$\\eta$-far” from $\\mathcal{I}$ by sampling only $\\mathcal{O}(tilt^3/(\\eta - \\varepsilon)^4)$ samples from the Hornsampler, where the tilt is the ratio of the maximum and the minimum (non-zero) probability masses of $\\mathcal{I}$. We also provide a prototype implementation of Flash and test three state-of-the-art samplers on a set of benchmarks"
authors:
- Ansuman Banerjee
- Shayak Chakraborty
- Sourav Chakraborty
- Kuldeep S. Meel
- Uddalok Sarkar
- Sayantan Sen
date: 2023-01-20 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *International Conference on Artificial Intelligence and Statistics (AISTATS)*
publication_types:
- '1'
selected: true
title: 'Testing of Horn Samplers'
url_pdf: https://proceedings.mlr.press/v206/banerjee23a/banerjee23a.pdf
# url_dataset: 
url_code: https://github.com/uddaloksarkar/flash
url_video: https://youtu.be/vP4i-a6SiBU
url_poster: https://virtual.aistats.org/media/PosterPDFs/AISTATS%202023/5771.png?t=1681236772.5409713
---


