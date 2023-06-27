---
abstract: "The past three decades have witnessed notable success in designing efficient SAT solvers, with modern solvers capable of solving industrial benchmarks containing millions of variables in just a few seconds. The success of modern SAT solvers owes to the widely-used CDCL algorithm, which lacks comprehensive theoretical investigation. Furthermore, it has been observed that CDCL solvers still struggle to deal with specific classes of benchmarks comprising only hundreds of variables, which contrasts with their widespread use in real-world applications. Consequently, there is an urgent need to uncover the inner workings of these seemingly weak yet powerful black boxes.
\n\n
In this paper, we present a first step towards this goal by introducing an approach called CausalSAT, which employs causal reasoning to gain insights into the functioning of modern SAT solvers. CausalSAT initially generates observational data from the execution of SAT solvers and learns a structured graph representing the causal relationships between the components of a SAT solver. Subsequently, given a query such as whether a clause with low literals blocks distance (LBD) has a higher clause utility, CausalSAT calculates the causal effect of LBD on clause utility and provides an answer to the question. We use CausalSAT to quantitatively verify hypotheses previously regarded as \"rules of thumb\" or empirical findings such as the query above or the notion that clauses with high LBD experience a rapid drop in utility over time. Moreover, CausalSAT can address previously unexplored questions, like which branching heuristic leads to greater clause utility in order to study the relationship between branching and clause management. Experimental evaluations using practical benchmarks demonstrate that CausalSAT effectively fits the data, verifies four \"rules of thumb\", and provides answers to three questions closely related to implementing modern solvers."
authors:
- Jiong Yang
- Arijit Shaw
- Teodora Baluta
- Mate Soos
- Kuldeep S. Meel
date: 2023-06-27 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Theory and Applications of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: 'Explaining SAT Solving Using Causal Reasoning'
url_code: https://github.com/meelgroup/causalsat
url_pdf: https://arxiv.org/pdf/2306.06294.pdf
#url_slides: files/slides/ganak_ijcai_pres.pdf
---

