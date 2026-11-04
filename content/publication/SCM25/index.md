---
title: 'Assessing the Quality of Binomial Samplers: A Statistical Distance Framework'
authors:
- Uddalok Sarkar
- Sourav Chakraborty
- Kuldeep S. Meel
date: '2025-01-01T00:00:00'
publication: In *Proceedings of International Conference on Computer-Aided Verification (CAV)*
publication_types:
- '1'
featured: false
math: true
abstract: Randomized algorithms depend on accurate sampling from probability distributions, as their correctness and performance hinge on the quality of the generated samples. However, even for common distributions like Binomial, exact sampling is computationally challenging, leading standard library implementations to rely on heuristics. These heuristics, while efficient, suffer from approximation and system representation errors, causing deviations from the ideal distribution. Although seemingly minor, such deviations can accumulate in downstream applications requiring large-scale sampling, potentially undermining algorithmic guarantees. In this work, we propose statistical distance as a robust metric for analyzing the quality of Binomial samplers, quantifying deviations from the ideal distribution. We derive rigorous bounds on the statistical distance for standard implementations and demonstrate the practical utility of our framework by enhancing APSEst, a DNF model counter, with improved
  reliability and error guarantees. To support practical adoption, we propose an interface extension that allows users to control and monitor statistical distance via explicit input/output parameters. Our findings emphasize the critical need for thorough and systematic error analysis in sampler design. As the first work to focus exclusively on Binomial samplers, our approach lays the groundwork for extending rigorous analysis to other common distributions, opening avenues for more robust and reliable randomized algorithms.
url_pdf: https://arxiv.org/pdf/2506.12061
tags:
- Distribution Testing
---
