---
abstract: 'Given a specification φ(X, Y ) over inputs X and output Y , defined over a background theory T, the problem of program synthesis is to design a program f such that Y = f (X) satisfies the specification φ. Over the past decade, syntax-guided synthesis (SyGuS) has emerged as a dominant approach to program synthesis where in addition to the specification φ, the end-user also specifies a grammar L to aid the underlying synthesis engine. This paper investigates the feasibility of synthesis techniques without grammar, a sub-class defined as T-constrained synthesis. 
We show that T-constrained synthesis can be reduced to DQF(T), i.e., to the problem of finding a witness of a dependency quantified formula modulo theory. When the underlying theory is bitvectors, the corresponding DQF problem can be further reduced to Dependency Quantified Boolean Formulas (DQBF). We rely on the progress in DQBF solving to design DQBF-based synthesizers that outpeform the domain-specific program synthesis techniques, thereby positioning DQBF as a core representation language for program synthesis. Our empirical analysis shows that T-constrained synthesis can achieve significantly better scalability than syntax-guided approaches. Furthermore, the general purpose DQBF solvers perform on par with domain-specific synthesis techniques.'
authors:
- Priyanka Golia
- Subhajit Roy
- Kuldeep S. Meel
date: 2021-04-30 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings International Joint Conference on Artificial Intelligence
  (IJCAI)*
publication_types:
- '1'
selected: true
title: 'Program Synthesis as Dependency Quantified Formula Modulo Theory'
url_code: https://github.com/meelgroup/DeQuS
url_pdf: https://arxiv.org/pdf/2105.09221.pdf
url_poster: files/slides/ijcai21_programsynthesis.pdf
url_video: https://recorder-v3.slideslive.com/?share=46475&s=387f015c-dba1-4d7d-8ada-7281aeb5b939
url_teaser: https://recorder-v3.slideslive.com/?share=46502&s=af7ac96c-7e3e-4019-bffb-b96e20c01828
---

