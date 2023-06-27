---
abstract: "The problem of model counting, also known as #SAT, is to compute the number of models or satisfying assignments of a given Boolean formula F. Model counting is a fundamental problem in computer science with a wide range of applications. In recent years, there has been a growing interest in using hashing-based techniques for approximate model counting that provide (ε,δ)-guarantees: i.e., the count returned is within a (1+ε)-factor of the exact count with confidence at least 1−δ. While hashing-based techniques attain reasonable scalability for large enough values of δ, their scalability is severely impacted for smaller values of δ, thereby preventing their adoption in application domains that require estimates with high confidence.
\n\n
The primary contribution of this paper is to address the Achilles heel of hashing-based techniques: we propose a novel approach based on rounding that allows us to achieve a significant reduction in runtime for smaller values of δ. The resulting counter, called RoundMC, achieves a substantial runtime performance improvement over the current state-of-the-art counter, ApproxMC. In particular, our extensive evaluation over a benchmark suite consisting of 1890 instances shows that RoundMC solves 204 more instances than ApproxMC, and achieves a 4× speedup over ApproxMC."
authors:
- Jiong Yang
- Kuldeep S. Meel
date: 2023-06-27 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Computer-Aided Verification
  (CAV)*


publication_types:
- '1'
selected: true
title: 'Rounding Meets Approximate Model Counting'
url_code: https://github.com/meelgroup/approxmc
url_pdf: https://arxiv.org/pdf/2305.09247.pdf
#url_slides: files/slides/CAV20_GSM_manthan.pdf
#url_video: https://www.youtube.com/watch?v=vGZtJNC8HbY
---
