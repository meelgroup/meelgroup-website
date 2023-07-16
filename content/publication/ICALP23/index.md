---
abstract: "Given a Boolean formula ϕ over n variables, the problem of model counting is to compute the number of solutions of ϕ. Model counting is a fundamental problem in computer science with wide-ranging applications. Owing to the #P-hardness of the problems, Stockmeyer initiated the study of the complexity of approximate counting. Stockmeyer showed that logn calls to an NP oracle are necessary and sufficient to achieve (ε,δ) guarantees. The hashing-based framework proposed by Stockmeyer has been very influential in designing practical counters over the past decade, wherein the SAT solver substitutes the NP oracle calls in practice. It is well known that an NP oracle does not fully capture the behavior of SAT solvers, as SAT solvers are also designed to provide satisfying assignments when a formula is satisfiable, without additional overhead. Accordingly, the notion of SAT oracle has been proposed to capture the behavior of SAT solver wherein given a Boolean formula, an SAT oracle returns a satisfying assignment if the formula is satisfiable or returns unsatisfiable otherwise. Since the practical state-of-the-art approximate counting techniques use SAT solvers, a natural question is whether an SAT oracle is more powerful than an NP oracle in the context of approximate model counting.
\n\n
The primary contribution of this work is to study the relative power of the NP oracle and SAT oracle in the context of approximate model counting. The previous techniques proposed in the context of an NP oracle are weak to provide strong bounds in the context of SAT oracle since, in contrast to an NP oracle that provides only one bit of information, a SAT oracle can provide n bits of information. We therefore develop a new methodology to achieve the main result: a SAT oracle is no more powerful than an NP oracle in the context of approximate model counting."
authors:
- Diptarka Chakraborty
- Sourav Chakraborty
- Gunjan Kumar
- Kuldeep S. Meel
date: 2023-07-04 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Colloquium on Automata, Languages and Programming (ICALP)*
publication_types:
- '1'
selected: true
title: 'Approximate Model Counting: Is SAT Oracle More Powerful than NP Oracle?'
url_pdf: https://arxiv.org/pdf/2306.10281.pdf
---

