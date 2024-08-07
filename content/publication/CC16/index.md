---
abstract: The ubiquity of hybrid CPU+GPU architectures has led to renewed interest
  in automatic data layout generation owing to the fact that data layouts have a large
  impact on performance, and that different data layouts yield the best performance
  on CPUs vs. GPUs. Unfortunately, current programming models still fail to provide
  an effective solution to the problem of automatic data layout generation for CPU+GPU
  processors. Specifically, the interaction among whole-program data layout optimizations,
  data movement optimizations, and mapping of kernels across heterogeneous cores poses
  a major challenge to current programming systems. In this paper, we introduce a
  novel two-level hierarchical formulation of the data layout and kernel mapping problem
  for modern heterogeneous architectures. The top level formulation targets data layouts
  and kernel mapping for the entire program for which we provide a polynomial- time
  solution using a graph-based shortest path algorithm that uses the data layouts
  for the code regions (sections) for a given processor computed in the bottom level
  formulation. The bottom level formulation deals with the data layout problem for
  a parallel code region on a given processor, which is NP-Hard, and we provide a
  greedy algorithm that uses an affinity graph to obtain approximate solutions. We
  have implemented this data layout transformation in the new Heterogeneous Habanero-C
  (H2C) parallel programming framework and propose performance models to characterize
  the data layout impact on both the CPU and GPU. Our data layout framework shows
  significant performance improvements of up to 2.9 (geometric mean 1.5) on a multicore
  CPU+GPU compared to the manually specified layouts for a set of parallel programs
  running on a heterogeneous platform consisting of an Intel Xeon CPU and a NVIDIA
  GPU. Further, our framework also shows performance improvements of up to 2.7 (geometric
  mean 1.6) on just the multicore CPU, demonstrating the applicability of our approach
  to both heterogeneous and homogeneous hardware platforms.
authors:
- Deepak Majeti
- Kuldeep S. Meel
- Raj Barik
- Vivek Sarkar
date: 2016-03-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Compiler Construction
  (CC)*
publication_types:
- '1'
selected: true
title: 'Automatic Data Layout Generation and Kernel Mapping for CPU+GPU Architectures '
url_pdf: https://www.cs.toronto.edu/~meel/Papers/CC2016.pdf
---

