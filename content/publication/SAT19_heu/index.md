---
abstract: Machine Learning (ML) models are widely used in decision making procedures
  in finance, medicine, education, etc. In these areas, ML outcomes can directly affect
  humans, e.g.\ by deciding whether a person should get a loan or be released from
  prison. Therefore, we cannot blindly rely on black box ML models and need to explain
  the decisions made by them. This motivated the development of a variety of ML-explainer
  systems, concrete examples of which include LIME and its successor ANCHOR. Due to
  the heuristic nature of explanations produced by existing tools, it is necessary
  to validate them. In this work, we propose a SAT-based method to assess the quality
  of explanations produced by ANCHOR We encode a trained ML model and an explanation
  for a given prediction as a propositional formula. Then, by using a state-of-the-art
  approximate model counter, we estimate the quality of the provided explanation as
  the number of solutions supporting it.
authors:
- Nina Narodytska
- Aditya Shrotri
- Kuldeep S. Meel
- Alexey Ignatiev
- Joao Marques Silva
date: 2019-05-05 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications
  of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: 'Assessing Heuristic Machine Learning Explanations with Model Counting  '
url_pdf: https://www.cs.toronto.edu/~meel/Papers/sat19nsmis.pdf
---

