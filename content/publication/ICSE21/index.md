---
abstract: 'Verifying security properties of deep neural networks (DNNs) is
becoming increasingly important. This paper introduces a new quantitative
verification framework for DNNs that can decide, with user-specified confidence,
whether a given logical property {\psi} defined over the space of inputs of the
given DNN holds for less than a user-specified threshold,{\theta}. We present
new algorithms that are scalable to large real-world models as well as proven to
be sound. Our approach requires only black-box access to the models. Further, it
certifies properties of both deterministic and non-deterministic DNNs. We
implement our approach in a tool called PROVERO. We apply PROVERO to the problem
of certifying adversarial robustness. In this context, PROVERO provides an
attack-agnostic measure of robustness for a given DNN and a test input. First,
we find that this metric has a strong statistical correlation with perturbation
bounds reported by 2 of the most prominent white-box attack strategies today.
Second, we show that PROVERO can quantitatively certify robustness with high
confidence in cases where the state-of-the-art qualitative verification tool
(ERAN) fails to produce conclusive results. Thus, quantitative verification
scales easily to large DNNs.'
authors:
- Teodora Baluta
- Zheng Leong Chua
- Kuldeep S. Meel
- Prateek Saxena
date: 2021-01-13 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *IEEE/ACM 43rd International Conference on Software Engineering (ICSE)*
publication_types:
- '1'
selected: true
title: 'Scalable Quantitative Verification For Deep Neural Networks'
url_code: https://github.com/teobaluta/PROVERO
url_pdf: https://arxiv.org/abs/2002.06864
url_slides: files/slides/NPAQ_talk.pptx
---

