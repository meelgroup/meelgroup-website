---
abstract: Hashing-based model counting has emerged as a promising approach for large-scale
  probabilistic inference on graphical models. A key component of these techniques
  is the use of xor-based 2-universal hash functions that operate over Boolean domains.
  Many counting problems arising in probabilistic inference are, however, naturally
  encoded over fi- nite discrete domains. Techniques based on bit-level (or Boolean)
  hash functions require these problems to be propositionalized, making it impossible
  to leverage the remarkable progress made in SMT (Satisfiability Modulo Theory) solvers
  that can reason directly over words (or bit-vectors). In this work, we present the
  first approximate model counter that uses word-level hashing functions, and can
  directly leverage the power of sophisticated SMT solvers. Empirical evaluation over
  an extensive suite of benchmarks demonstrates the promise of the approach.
authors:
- Supratik Chakraborty
- Kuldeep S. Meel
- Rakesh Mistry
- Moshe Y. Vardi
date: 2016-06-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'Approximate Probabilistic Inference via Word-Level Counting '
url_code: https://bitbucket.org/kuldeepmeel/smtapproxmc/src/master/
url_pdf: http://www.comp.nus.edu.sg/~meel/Papers/AAAI16.pdf
url_slides: files/slides/AAAIv2.pdf
---

