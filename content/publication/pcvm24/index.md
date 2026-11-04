---
title: On the Feasibility of Forgetting in Data Streams
authors:
- A. Pavan
- Sourav  Chakraborty
- N. V. Vinodchandran
- Kuldeep S. Meel
date: '2024-01-01T00:00:00'
publication: In *Proceedings of ACM Symposium on Principles of Database Systems (PODS)*
publication_types:
- '1'
featured: false
math: true
abstract: 'In today''s digital age, it is becoming increasingly prevalent to retain digital footprints in the cloud indefinitely. Nonetheless, there is a valid argument that entities should have the authority to decide whether their personal data remains within a specific database or is expunged. Indeed, nations across the globe are increasingly enacting legislation to uphold the “Right To Be Forgotten” for individuals. Investigating computational challenges, including the formalization and implementation of this notion, is crucial due to its relevance in the domains of data privacy and management. This work introduces a new streaming model: the `Right to be Forgotten Data Streaming Model'' (RDFS). This work systematically investigates computational challenges that arise while incorporating the notion of the right to be forgotten. Our initial considerations reveal that even estimating (sum of the frequencies of elements) of the stream is a non-trivial problem in this model. Based on the
  initial investigations, we focus on a modified model which we call α-RFDS where we limit the number of forget operations to be at most α fraction. In this modified model, we focus on estimating F0 (number of distinct elements) and F1. We present algorithms and establish almost-matching lower bounds on the space complexity for these computational tasks.'
url_pdf: https://www.cs.toronto.edu/~meel/Papers/pods24-pcvm.pdf
tags:
- Data Streams
---
