---
abstract: "Answer Set Programming (ASP) has emerged as a promising paradigm in knowledge representation and automated reasoning owing to its ability to model hard combinatorial problems from diverse domains in a natural way.  Building on advances in propositional SAT solving, the past two decades have witnessed the emergence of well-engineered systems for solving the answer set satisfiability problem, i.e., finding models or answer sets for a given answer set program.  In recent years, there has been growing interest in problems beyond satisfiability, such as model counting, in the context of ASP. Akin to the early days of propositional model counting, state-of-the-art exact answer set counters do not scale well beyond small instances. Exact ASP counters struggle with handling larger input formulas. The primary contribution of this paper is a new ASP counting framework, called sharpASP, which counts answer sets avoiding larger input formulas.  This relies on an alternative way of defining answer sets that allows for the lifting of key techniques developed in the context of propositional model counting. Our extensive empirical analysis over $1470$ benchmarks demonstrates significant performance gain over current state-of-the-art exact answer set counters.  Specifically, by using sharpASP, we were able to solve $1062$ benchmarks with PAR2 score of $3082$ whereas using prior state-of-the-art, we could only solve $895$ benchmarks with a PAR2 score of $4205$, all other experimental conditions being the same.
"

authors:
- Mohimenul Kabir,
- Supratik Chakraborty,
- Kuldeep S Meel
date: 2024-02-21 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'Exact ASP Counting with Compact Encodings'
url_pdf: 'https://arxiv.org/pdf/2312.11936v1.pdf'
---