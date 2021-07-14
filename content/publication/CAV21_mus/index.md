---
abstract: 'Given an unsatisfiable Boolean formula F in CNF, an unsatisfiable subset of clauses U of F is called Minimal Unsatisfiable Subset (MUS) if every proper subset of U is satisfiable. Since MUSes serve as explanations for the unsatisfiability of F, MUSes find applications in a wide variety of domains. The availability of efficient SAT solvers has aided the development of scalable techniques for finding and enumerating MUSes in the past two decades. Building on the recent developments in the design of scalable model counting techniques for SAT, Bendik and Meel initiated the study of MUS counting techniques. They succeeded in designing the first approximate MUS counter, AMUSIC, that does not rely on exhaustive MUS enumeration. AMUSIC, however, suffers from two shortcomings: the lack of exact estimates and limited scalability due to its reliance on 3-QBF solvers. In this work, we address the two shortcomings of AMUSIC by designing the first exact MUS counter, CountMUST, that does not rely on exhaustive enumeration. CountMUST circumvents the need for 3-QBF solvers by reducing the problem of MUS counting to projected model counting. While projected model counting is #NP-hard, the past few years have witnessed the development of scalable projected model counters. An extensive empirical evaluation demonstrates that CountMUST successfully returns MUS count for 1500 instances while AMUSIC and enumeration-based techniques could only handle up to 833 instances.'
authors:
- Jaroslav Bendik
- Kuldeep S. Meel
date: 2021-05-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Computer-Aided Verification (CAV), 2021.*
publication_types:
- '1'
selected: true
title: 'Counting Minimal Unsatisfiable Subsets'
#url_code: https://github.com/meelgroup/ganak
url_pdf: 
#url_slides: files/slides/ganak_ijcai_pres.pdf
---

