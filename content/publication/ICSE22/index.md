---
abstract: 'Owing to the pervasiveness of software in our modern lives, software systems have evolved to be highly configurable. Combinatorial testing has emerged as a dominant paradigm for testing highly configurable systems. Often constraints are employed to define the environments where a given system under test (SUT) is expected to work. Therefore, there has been a sustained interest in designing constraint-based test suite generation techniques. The holy grail of test suite generation techniques is to achieve higher ttt-wise coverage. While it is known that most of the software errors are discovered for ttt up to 6 but the proposal of most test generation techniques is often accompanied with empirical evaluation for only t=2. The primary reason behind such an unsatisfactory situation is lack of scalable techniques that can estimate ttt-wise coverage for a given set of samples or the maximum achievable t-wise coverage under a given set of constraints. The primary technical contribution of this work is the design of scalable algorithms to estimate (i) ttt-wise coverage for a given set of tests, and (ii) maximum ttt-wise coverage for a given set of constraints. In particular, we design a scalable framework ApproxCov that takes in a test set U, tolerance parameter varepsilon, confidence parameter \delta, and returns an estimate that is guaranteed to be within (1\pm\varepsilon)-factor of the ground truth with probability at least1-\delta. For a given formula F, we design a scalable framework ApproxMaxCo that is guaranteed to approximate within (1\pm \varepsilon) factor, the maximum achievable t-wise coverage under F. Our comprehensive evaluation demonstrates that ApproxCov and ApproxMaxCov can handle benchmarks that is beyond the reach of current state of the art approaches. To the best of our knowledge, we present the first comparative study of different sampling techniques for values of t>=4 for large benchmarks. We believe that the availability of ApproxCov and ApproxMaxCov will enable test suite designers to evaluate the effectiveness of their generators and thereby contributing to improvement of combinatorial testing techniques.'
authors:
- Eduard Baranov
- Sourav Chakraborty
- Axel Legay
- Kuldeep S. Meel
- N.V. Vinodchandran
date: 2022-05-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Software Engineering (ICSE)*
publication_types:
- '1'
selected: true
title: 'A Scalable t-wise Coverage Estimator'
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/icse22.pdf
---

