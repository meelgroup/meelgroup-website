---
abstract: Given an unsatisfiable set of constraints F, a maximal satisfiable subset (MSS) is a maximal subset of constraints C ⊆ F such that C is satisfiable. Over the past two decades, the steady improvement in runtime performance of algorithms for finding MSSes has led to increased adoption of MSSbased techniques in a wide variety of domains. Motivated by the progress in finding an MSS, the past decade has witnessed a surge of interest in the design of algorithmic techniques to enumerate all the MSSes, which has subsequently led to a discovery of new applications utilizing enumeration of MSSes. The development of techniques for finding and enumeration of MSSes mirrors a similar phenomenon of finding and enumeration of SAT solutions in the early 2000s, which subsequently motivated the design of algorithmic techniques for model counting. In a similar spirit, we undertake a study to investigate the feasibility of MSS counting techniques. In particular, the focus point of our investigation is to answer whether one can design efficient MSS counting techniques that do not rely on explicit MSS enumeration. The primary contribution of this work is an affirmative answer to the above question in the form of a novel algorithm. The algorithm uses a novel architecture of a wrapper W and a remainder R such that the desired MSS count can be expressed as |W|−|R|. To efficiently compute |W| and |R|, the algorithm relies on the advances in projected model counting. Our empirical evaluation demonstrates that our approach can scale to instances clearly beyond the reach of enumeration-based techniques.
authors:
- Jaroslav Bendík
- Kuldeep S. Meel
date: 2021-01-11 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: Counting Maximal Satisfiable Subsets
url_pdf: files/publications/7956.BendikJ_preprint.pdf
---

