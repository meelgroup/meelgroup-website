---
abstract: 'The past two decades have witnessed an unprecedented improvement in runtime performance of SAT solvers owing to clever software engineering and creative design of data structure. Yet, most entries in the annual SAT competition retain the core architecture of MiniSat, which was designed from the perspective of single core CPU architectures. On the other hand, since 2005, there has been a significant shift to heterogeneous architectures owing to the impending end of Dennard scaling. Consequently, it is no coincidence that the recent breakthroughs in computer science have significantly utilized opportunities offered by such heterogeneous architectures. The primary contribution of this work is a novel multi-threaded CDCL-based framework, called GpuShareSat, designed to take advantage of CPU+GPU achitecture. The core underlying principle of our approach is to divide the tasks among CPU and GPU so as to attempt to achieve the best of both worlds. We observe that efficient bit-vector based operations can allow a GPU to efficiently determine the usefulness of a learnt clause to different threads and accordingly notifies the thread of the presence of relevant clauses in different threads. The approach of checking all clauses against all different assignments from different threads allows the GPU to exploit its potential for massive parallelism through clever group-testing strategy and bitwise operations. Our setup efficiently distributes the work between the CPU and the GPU, each performing the task they are best at to further the speed of parallel SAT solving. To demonstrate the practical efficiency of our framework, we augment the state of the art multi-threaded solvers glucose-syrup with GpuShareSat and perform detailed analysis on benchmarks from SAT 2020 competition. Our empirical analysis demonstrates that augmentation of glucose-syrup augmented with GpuShareSat solves 22 more instances than glucose-syrup alone.'
authors:
- Nicolas Prevot
- Mate Soos
- Kuldeep S. Meel
date: 2021-05-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications of Satisfiability Testing (SAT), 2021*.
publication_types:
- '1'
selected: true
title: 'Leveraging GPUs for Effective Clause Sharing in Parallel SAT Solving'
#url_code: https://github.com/meelgroup/ganak
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/sat21-psm.pdf
#url_slides: files/slides/ganak_ijcai_pres.pdf
---

