---
title: Distance Estimation for High-Dimensional Discrete Distributions
authors:
- Kuldeep S. Meel
- Gunjan Kumar
- Yash Pote
date: '2025-01-01T00:00:00'
publication: In *Proceedings of International Conference on Artificial Intelligence and Statistics (AISTATS)*
publication_types:
- '1'
featured: false
math: true
abstract: Given two distributions 𝒫 and 𝒬 over a high-dimensional domain {0,1}^n, and a parameter ε, the goal of distance estimation is to determine the statistical distance between 𝒫 and 𝒬, up to an additive tolerance ±ε. Since exponential lower bounds (in n) are known for the problem in the standard sampling model, research has focused on richer query models where one can draw conditional samples. This paper presents the first polynomial query distance estimator in the conditional sampling model (𝖢𝖮𝖭𝖣). We base our algorithm on the relatively weaker subcube conditional sampling (𝖲𝖴𝖡𝖢𝖮𝖭𝖣) oracle, which draws samples from the distribution conditioned on some of the dimensions. 𝖲𝖴𝖡𝖢𝖮𝖭𝖣 is a promising model for widespread practical use because it captures the natural behavior of discrete samplers. Our algorithm makes 𝒪̃(n^3/ε^5) queries to 𝖲𝖴𝖡𝖢𝖮𝖭𝖣.
url_pdf: https://arxiv.org/pdf/2308.04264
tags:
- Distribution Testing
---
