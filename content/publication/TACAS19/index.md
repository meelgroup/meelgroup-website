---
abstract: 'Previous work on applying Knowledge compilation has focused on uniform
  sampling over all the variables. Since the constraints are written in high level
  languages such as Verilog, the popular CNF encoding schemes as Tseitin encoding
  introduces additional auxiliary variables. The resulting CNF formulas are not equivalent
  but equisatisfiable. In particular, for a formula $G$ specified in high level language
  we obtain a CNF formula F such that $G (X) = \exists Y F(X,Y)$. This makes one wonder
  if it is possible to extend Knowledge compilation based techniques to sample over
  a subset of variables. Furthermore, languages such as Verilog allow specification
  of weights to user-defined constraints, so there is a need to sample according to
  the posterior distribution. In this paper, we provide affirmative question to the
  above two questions: We propose KUS that samples over user defined subset of variables
  from posterior distribution for a given prior distribution defined over product
  spaces.'
authors:
- Rahul Gupta
- Shubham Sharma
- Subhajit Roy
- Kuldeep S. Meel
date: 2019-04-04 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Tools and Algorithms for the Construction and Analysis
  of Systems (TACAS)*
publication_types:
- '1'
selected: true
title: 'WAPS: Weighted and Projected Sampling '
url_code: https://github.com/meelgroup/waps
url_pdf: https://www.cs.toronto.edu/~meel/Papers/tacas19.pdf
url_slides: files/slides/TACAS19.pdf
---

