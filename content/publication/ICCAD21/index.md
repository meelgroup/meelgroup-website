---
abstract: 'Given a Boolean specification between a set of inputs and outputs, the problem of Boolean functional synthesis is to synthesise each output as a function of inputs such that the specification is met. Although the past few years have witnessed intense algorithmic development, accomplishing scalability remains the holy grail. The state-of-the-art approach combines machine learning and automated reasoningto synthesise Boolean functions efficiently. In this paper, we propose fouralgorithmic improvements for a data-driven framework for functional synthesis: using a dependency-driven multi-classifier to learn candidatefunction, extracting uniquely defined functions by interpolation, variables retention, and using lexicographic MaxSAT to repair candidates.
We implement these improvements in the state-of-the-art framework, called Manthan. The proposed framework is called Manthan2. Manthan2 shows significantly improved runtime performance compared to Manthan. In an extensive experimental evaluation on 609 benchmarks, Manthan2 is able to synthesise a Boolean function vector for 509 instances compared to 356 instances solved by Manthan – an increment of 153 instances over the state-of-the-art. To put this into perspective, Manthan improved on the prior state-of-the-art by only 76 instances.'
authors:
- Priyanka Golia
- Friedrich Slivovsky
- Subhajit Roy
- Kuldeep S. Meel
date: 2021-07-13 00:00:00
highlight: true
image_preview: ''
math: true
publication: "In Proceedings of International Conference On Computer Aided Design (ICCAD)"
publication_types:
- '1'
selected: true
title: 'Engineering an Efficient Boolean Functional Synthesis Engine'
#url_code: https://github.com/meelgroup/dequs
url_pdf: https://arxiv.org/pdf/2108.05717.pdf
#url_slides: files/slides/ganak_ijcai_pres.pdf
---
