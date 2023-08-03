---
abstract: 'Recent years have seen an unprecedented adoption of artificial intelligence
  in wide variety of applications ranging from medical diagnosis, automobile, security
  to aircraft collision avoidance. Probabilistic reasoning is a key component of such
  modern artificial intelligence systems. Sampling techniques form the core of the
  state of the art probabilistic reasoning systems. In contrast to testing for deterministic
  programs, where one trace is sufficient to prove the existence of a bug; such is
  not the case for samplers as one sample is typically not sufficient to prove non-conformity
  of the sampler to the desired distribution. This makes one wonder: whether it is
  possible to design testing methodology to test whether a sampler under test generates
  samples close to a given distribution. The primary contribution of this paper is
  a positive answer to the above question: We design, to the best of our knowledge,
  the first algorithmic framework, Barbarik, to test whether the distribution generated
  by $\varepsilon-$close or $\eta-$far from the uniform distribution. In contrast
  to the sampling techniques that require an exponential or sub-exponential number
  of samples for sampler whose support can be represented by $n$ bits, Barbarik requires
  only $\mathcal{O}(1/(\eta-\varepsilon)^2)$ samples. We present a prototype implementation
  of Barbarik and use it to test three state of the art uniform samplers over the
  support defined by combinatorial constraints. Barbarik is able to provide a certificate
  of uniformity to one sampler and demonstrate non-uniformity for the other two samplers.'
authors:
- Sourav Chakraborty
- Kuldeep S. Meel
date: 2019-01-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'On testing of Uniform Samplers '
url_code: https://github.com/meelgroup/barbarik
url_pdf: https://www.cs.toronto.edu/~meel/Papers/aaai19-cm.pdf
url_slides: files/slides/AAAI19_testing.pdf
---

