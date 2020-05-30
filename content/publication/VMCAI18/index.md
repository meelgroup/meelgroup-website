---
abstract: Quantitative information flow measurement techniques have been proven to
  be successful in detecting leakage of confidential information from programs. Modern
  approaches are based on formal methods, relying on program analysis to produce a
  SAT formula representing the program's behavior, and model counting to measure the
  possible information flow. However, while program analysis scales to large codebases
  like the OpenSSL project, the formulas produced are too complex for analysis with
  precise model counting. In this paper we use the approximate model counter ApproxMC2
  to quantify information flow. We show that ApproxMC2 is able to provide a large
  performance increase for a very small loss of precision, allowing the analysis of
  SAT formulas produced from complex code. We call the resulting technique ApproxFlow
  and test it on a large set of benchmarks against the state of the art. Finally,
  we show that ApproxFlow can evaluate the leakage incurred by the Heartbleed OpenSSL
  bug, contrarily to the state of the art.
authors:
- Fabrizio Biondi
- Michael Enescu
- Annelie Heuser
- Axel Legay
- Kuldeep S. Meel
- Jean Quilbeuf
date: 2018-01-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Verification, Model Checking,
  and Abstract Interpretation*
publication_types:
- '1'
selected: true
title: Scalable Approximation of Quantitative Information Flow in Programs
url_pdf: http://www.comp.nus.edu.sg/~meel/Papers/vmcai18.pdf
url_slides: files/slides/presentation_vmcai18.pdf
---

