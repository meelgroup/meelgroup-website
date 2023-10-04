---
abstract: Fairness in machine learning has attained significant focus due to the widespread application in high-stake decision-making tasks. Unregulated machine learning classifiers can exhibit bias towards certain demographic groups in data, thus the quantification and mitigation of classifier bias is a central concern in fairness in machine learning. In this paper, we aim to quantify the influence of different features in a dataset on the bias of a classifier. To do this, we introduce the Fairness Influence Function (FIF). This function breaks down bias into its components among individual features and the intersection of multiple features. The key idea is to represent existing group fairness metrics as the difference of the scaled conditional variances in the classifier’s prediction and apply a decomposition of variance according to global sensitivity analysis. To estimate FIFs, we instantiate an algorithm FairXplainer that applies variance decomposition of classifier’s prediction following local regression. Experiments demonstrate that FairXplainer captures FIFs of individual feature and intersectional features, provides a better approximation of bias based on FIFs, demonstrates higher correlation of FIFs with fairness interventions, and detects changes in bias due to fairness affirmative/punitive actions in the classifier.
authors:
- Bishwamittra Ghosh
- Debabrota Basu
- Kuldeep S. Meel
date: 2023-06-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of FAccT*
publication_types:
- '1'
selected: true
title: 'How Biased are Your Features?: Computing Fairness Influence Functions with Global Sensitivity Analysis'
url_code: https://github.com/ReAILe/bias-explainer
url_pdf: https://arxiv.org/pdf/2206.00667.pdf
---

