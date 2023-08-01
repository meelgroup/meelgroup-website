---
abstract: "The most widely studied explainable AI (XAI) approaches are unsound. This is the case with well-known model-agnostic explanation approaches, and it is also the case with approaches based on saliency maps. One solution is to consider intrinsic interpretability, which does not exhibit the drawback of unsoundness. Unfortunately, intrinsic interpretability can display unwieldy explanation redundancy. Formal explainability represents the alternative to these non-rigorous approaches, with one example being PI-explanations. Unfortunately, PI-explanations also exhibit important drawbacks, the most visible of which is arguably their size. Recently, it has been observed that the (absolute) rigor of PI-explanations can be traded off for a smaller explanation size, by computing the so-called relevant sets. Given some positive {\delta}, a set S of features is {\delta}-relevant if, when the features in S are fixed, the probability of getting the target class exceeds {\delta}. However, even for very simple classifiers, the complexity of computing relevant sets of features is prohibitive, with the decision problem being NPPP-complete for circuit-based classifiers. In contrast with earlier negative results, this paper investigates practical approaches for computing relevant sets for a number of widely used classifiers that include Decision Trees (DTs), Naive Bayes Classifiers (NBCs), and several families of classifiers obtained from propositional languages. Moreover, the paper shows that, in practice, and for these families of classifiers, relevant sets are easy to compute. Furthermore, the experiments confirm that succinct sets of relevant features can be obtained for the families of classifiers considered."

authors:
- Yacine Izza 
- Xuanxiang Huang 
- Alexey Ignatiev 
- Nina Narodytska
- Martin C. Cooper
- Joao Marques-Silva
date: 2023-04-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Int. J. Approx. Reason. (IJAR)*
publication_types:
- '2'
selected: true
title: 'On computing probabilistic abductive explanations'
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0888613X23000701?via%3Dihub
---