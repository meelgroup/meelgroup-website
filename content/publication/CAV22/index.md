---
abstract: "Quantified information flow (QIF) has emerged as a rigorous approach to quantitatively measure confidentiality; the information-theoretic underpinning of QIF allows the end-users to link the computed quantities with the computational effort required on the part of the adversary to gain access to desired confidential information. In this work, we focus on the estimation of Shannon entropy for a given program Π. As a first step, we focus on the case wherein a Boolean formula φ(X, Y ) captures the relationship between inputs X and output Y of Π. Such formulas φ(X, Y ) have the property that for every valuation to X, there exists exactly one valuation to Y such that φ is satisfied. The existing techniques require O(2 m ) model counting queries, where m = |Y |. 
We propose the first efficient algorithmic technique, called EntropyEstimation to estimate the Shannon entropy of φ with PAC-style guarantees, i.e., the computed estimate is guaranteed to lie within a (1 ± ε)-factor of the ground truth with confidence at least 1−δ. Furthermore, EntropyEstimation makes only O( min(m,n)) counting and sampling queries, where m = |Y |, and n = |X|, thereby achieving a significant reduction in the number of model counting queries. We demonstrate the practical efficiency of our algorithmic framework via a detailed experimental evaluation. Our evaluation demonstrates that the proposed framework scales to the formulas beyond the reach of the previously known approaches."
authors:
- Priyanka Golia
- Brendan Juba
- Kuldeep S. Meel
date: 2022-05-09 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of 34nd International Conference on Computer-Aided Verification
  (CAV)*


publication_types:
- '1'
selected: true
title: 'A Scalable Shannon Entropy Estimator'
url_code: https://github.com/meelgroup/EntropyEstimation
url_pdf: files/publications/cav-22-entropy.pdf
#url_slides: files/slides/CAV20_GSM_manthan.pdf
#url_video: https://www.youtube.com/watch?v=vGZtJNC8HbY
---
