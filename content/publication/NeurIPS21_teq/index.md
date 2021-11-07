---
abstract: "Probabilistic circuits (PCs) are a powerful modeling framework for representing tractable probability distributions over combinatorial spaces. In machine learning and probabilistic programming, one is often interested in understanding whether the distributions learned using PCs are close to the desired distribution. Thus, given two probabilistic circuits, a fundamental problem of interest is to determine whether their distributions are close to each other.

The primary contribution of this paper is a closeness test for PCs with respect to the total variation distance metric. Our algorithm utilizes two common PC queries, counting and sampling. In particular, we provide a poly-time probabilistic algorithm to check the closeness of two PCs, when the PCs support tractable approximate counting and sampling. We demonstrate the practical efficiency of our algorithmic framework via a detailed experimental evaluation of a prototype implementation against a set of 375 PC benchmarks. We find that our test correctly decides the closeness of all 375 PCs within 3600 seconds. "
authors:
- Yash Pote
- Kuldeep S. Meel
date: 2021-11-07 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Advances in Neural Information Processing Systems (NeurIPS)*
publication_types:
- '1'
selected: true
title: 'Testing Probabilistic Circuits'
url_pdf: files/publications/NeurIPS21_PCtest.pdf
#url_slides: files/slides/Neurips20-MPC.pdf
#url_video: https://slideslive.com/38936618/on-testing-of-samplers?ref=account-81660-history
---

