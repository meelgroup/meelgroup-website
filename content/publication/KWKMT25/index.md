---
title: Verification of the CVM Algorithm with a Functional Probabilistic Invariant
authors:
- Emin Karayel
- Seng Joe Watt
- Derek Khu
- Kuldeep S. Meel
- Yong Kiam Tan
date: '2025-01-01T00:00:00'
publication: In *Interactive Theorem Proving (ITP)*
publication_types:
- '1'
featured: false
math: true
abstract: Estimating the number of distinct elements in a data stream is a classic problem with numerous applications in computer science. We formalize a recent, remarkably simple, randomized algorithm for this problem due to Chakraborty, Vinodchandran, and Meel (called the CVM algorithm). Their algorithm deviated considerably from the state of the art, due to its avoidance of intricate derandomization techniques, while still maintaining a close-to-optimal logarithmic space complexity. Central to our formalization is a new proof technique based on functional probabilistic invariants, which allows us to derive concentration bounds using the Cramer-Chernoff method without relying on independence. This simplifies the formal analysis considerably compared to the original proof by Chakraborty et al. Moreover, our technique opens up the possible algorithm design space; we demonstrate this by introducing and verifying a new variant of the CVM algorithm that is both total and unbiased - neither
  of which is a property of the original algorithm. In this paper, we introduce the proof technique, describe its use in mechanizing both versions of the CVM algorithm in Isabelle/HOL, and present a supporting formalized library on negatively associated random variables used to verify the latter variant.
url_pdf: https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ITP.2025.34
tags:
- Formal Methods
---
