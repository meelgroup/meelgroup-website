---
abstract: "First-order model counting (FOMC) is the problem of counting the number of models of a sentence in first-order logic. Since lifted inference techniques rely on reductions to variants of FOMC, the design of scalable methods for FOMC has attracted attention from both theoreticians and practitioners over the past decade. Recently, a new approach based on first-order knowledge compilation was proposed. This approach, called Crane, instead of simply providing the final count, generates definitions of (possibly recursive) functions that can be evaluated with different arguments to compute the model count for any domain size. However, this approach is not fully automated, as it requires manual evaluation of the constructed functions. The primary contribution of this work is a fully automated compilation algorithm, called Crane2, which transforms the function definitions into C++ code equipped with arbitrary-precision arithmetic. These additions allow the new FOMC algorithm to scale to domain sizes over 500,000 times larger than the current state of the art, as demonstrated through experimental results."
authors:
- Ananth K. Kidambi
- Guramrit Singh
- Paulius Dilkas
- Kuldeep S. Meel
date: 2025-06-10 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: 'Towards Practical First-Order Model Counting'
url_pdf: 'https://dilkas.github.io/pdf/fomc2.pdf'
---


