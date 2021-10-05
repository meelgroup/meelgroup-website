---
abstract: 'Given a formula the problem of uniform sampling seeks to sample solutions of uniformly at random. Uniform sampling is a fundamental problem with a wide variety of applications. The computational intractability of uniform sampling has led to the development of several samplers that heavily rely on heuristics and are not accompanied by theoretical analysis of their distribution. Recently, Chakraborty and Meel (2019) designed the first scalable sampling tester, Barbarik, based on a grey-box sampling technique for testing if the distribution, according to which the given sampler is sampling, is close to the uniform or far from uniform. While the theoretical analysis of Barbarik provides only unconditional soundness guarantees, the empirical evaluation of Barbarik did show its success in determining that some of the off-the-shelf samplers were far from a uniform sampler.
The availability of Barbarik has the potential to spur development of samplers and testing techniques such that developers can design sampling methods that can be accepted by Barbarik even though these samplers may not be amenable to a detailed mathematical analysis. In this paper, we present the realization of this aforementioned promise. Based on the flexibility offered by CryptoMiniSat, we design a sampler CMSGen that promises the achievement of sweet spot of the quality of distributions and runtime performance. In particular, CMSGen achieves significant runtime performance improvement over the existing samplers. We conduct two case studies, and demonstrate that the usage of CMSGen leads to significant runtime improvements in the context of combinatorial testing and functional synthesis.
A salient strength of our work is the simplicity of CMSGen, which stands in contrast to complicated algorithmic schemes developed in the past that fail to attain desired quality of distributions with practical runtime performance.'
authors:
- Priyanka Golia
- Mate Soos
- Sourav Chakraborty
- Kuldeep S. Meel
date: 2021-07-11 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings Formal Methods in Computer-Aided Design
  (FMCAD)*
publication_types:
- '1'
selected: true
title: 'Designing Samplers is Easy: The Boon of Testers'
url_code: https://github.com/meelgroup/cmsgen
#url_pdf: https://arxiv.org/pdf/2105.09221.pdf
url_pdf: files/publications/fmcad21_shakuni.pdf
url_slides: files/slides/fmcad21.pdf
url_video: https://www.youtube.com/watch?v=CKa4NmEg7Hk
---

