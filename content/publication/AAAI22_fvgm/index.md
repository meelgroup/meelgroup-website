---
abstract: 'In recent years, machine learning (ML) algorithms have been deployed in safety-critical and high-stake decision-making, where the fairness of algorithms is of paramount importance. Fairness in ML centers on detecting bias towards certain demographic populations induced by an ML classifier and proposes algorithmic solutions to mitigate the bias with respect to different fairness definitions. To this end, several fairness verifiers have been proposed that compute the bias in the prediction of an ML classifier -- essentially beyond a finite dataset -- given the probability distribution of input features. In the context of verifying linear classifiers, existing fairness verifiers are limited by accuracy due to imprecise modelling of correlations among features and scalability due to restrictive formulations of the classifiers as SSAT or SMT formulas or by sampling. 

In this paper, we propose an efficient fairness verifier, called FVGM, that encodes the correlations among features as a Bayesian network. In contrast to existing verifiers, FVGM proposes a stochastic subset-sum based approach for verifying linear classifiers. Experimentally, we show that FVGM leads to an accurate and scalable assessment for more diverse families of fairness-enhancing algorithms, fairness attacks, and group/causal fairness metrics than the state-of-the-art. We also demonstrate that FVGM facilitates the computation of fairness influence functions as a stepping stone to detect the source of bias induced by subsets of features.'
authors:
- Bishwamittra Ghosh
- Debabrota Basu
- Kuldeep S. Meel
date: 2022-06-06 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'Algorithmic Fairness Verification with Graphical Models'
url_code: https://github.com/meelgroup/justicia
url_pdf: https://arxiv.org/pdf/2109.09447.pdf
---

