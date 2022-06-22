---
abstract: "The problem of uniform sampling is, given a formula F , sample solutions of F uniformly atrandom from the solution space of F . Uniform sampling is a fundamental problem with widespread applications, including configuration testing, bug synthesis, function synthesis, and many more. State-of-the-art approaches for uniform sampling have a trade-off between scalability and theoretical guarantees. Many state of the art uniform samplers do not provide any theoretical guarantees on the distribution of samples generated, however, empirically they have shown promising results. In such cases, the main challenge is to test whether the distribution according to which samples are generated is indeed uniform or not.
Recently, Chakraborty and Meel (2019) designed the first scalable sampling tester, Barbarik, based on a grey-box sampling technique for testing if the distribution, according to which the given sampler is sampling, is close to the uniform or far from uniform. They were able to show that many off-the-self samplers are far from a uniform sampler. The availability of Barbarik increased the test-driven development of samplers. More recently, Golia, Soos, Chakraborty and Meel (2021), designed a uniform like sampler, CMSGen, which was shown to be accepted by Barbarik on all the instances. However, CMSGen does not provide any theoretical analysis of the sampling quality. CMSGen leads us to observe the need for a tester to provide a quantitative answer to determine the quality of underlying samplers instead of merely a qualitative answer of Accept or Reject. Towards this goal, we design a computational hardness-based tester ScalBarbarik that provides a more nuanced analysis of the quality of a sampler. ScalBarbarik allows more expressive measurement of the quality of the underlying samplers. We empirically show that the state-of-the-art sampler, CMSGen is not accepted as a uniform-like sampler by ScalBarbarik. Furthermore, we show that ScalBarbarik can be used to design a sampler that can achieve balance between scalability and uniformity."
authors:
- Mate Soos
- Priyanka Golia
- Sourav Chakraborty
- Kuldeep S. Meel
date: 2022-05-09 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming (CP)*
publication_types:
- '1'
selected: true
title: 'On Quantitative Testing of Samplers'
url_pdf: files/publications/cp22_shakuni.pdf
#url_dataset: https://doi.org/10.5281/zenodo.5526835
url_code: https://github.com/meelgroup/scalbarbarik
# url_video: https://www.youtube.com/watch?v=vCc6jpOm04Y&feature=youtu.be
---

