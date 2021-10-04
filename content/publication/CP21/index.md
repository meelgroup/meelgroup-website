---
abstract: "Despite the NP-completeness of Boolean satisfiability, modern SAT solvers are routinely able to handle large practical instances, and consequently have found wide ranging applications. The primary workhorse behind the success of SAT solvers is the widely acclaimed Conflict Driven Clause Learning (CDCL) paradigm, which was originally proposed in the context of Boolean formulas in CNF. The wide ranging applications of SAT solvers have highlighted that for several domains, CNF is not a natural representation and the reliance of modern SAT solvers on resolution proof system limit their ability to efficiently solve several families of constraints. Consequently, the past decade has witnessed the design of solvers with native support for constraints such as Pseudo-Boolean (PB) and CNF-XOR. 
The primary contribution of our work is an efficient solver engineered for PB-XOR formulas, i.e., formulas consisting of a conjunction of PB and XOR constraints. We first observe that a simple adaption of CNF-XOR architecture does not provide an improvement over baseline; our analysis highlights the need for careful engineering of the order of propagations. To this end, we propose three different tactics, all of which achieve significant performance improvements over the baseline. Our work is motivated by applications arising from binarized neural network verification where the verification of properties such as robustness, fairness, trojan attacks can be reduced to model counting queries; the state of the art model counters reduce counting to polynomially many SAT queries over the original formula conjuncted with randomly generated XOR constraints. To this end, we augment ApproxMC with LinPB and we call the resulting counter as ApproxMCPB. In an extensive empirical comparison over 1076 benchmarks, we observe that ApproxMCPB can solve 912 instances while the baseline version of ApproxMC4 (augmented with CryptoMiniSat) can solve only 802 instances."
authors:
- Jiong Yang
- Kuldeep S. Meel
date: 2021-07-28 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming (CP)*
publication_types:
- '1'
selected: true
title: 'Engineering an Efficient PB-XOR Solver'
url_pdf: files/publications/CP21.pdf
url_dataset: https://doi.org/10.5281/zenodo.5526835
url_code: https://github.com/meelgroup/linpb
# url_video: https://www.youtube.com/watch?v=vCc6jpOm04Y&feature=youtu.be
---

