---
abstract: Given an unsatisfiable formula F in CNF, i.e. a set of clauses, the problem
  of Minimal Unsatisfiable Subset (MUS) seeks to identify the minimal subset of clauses
  N ⊆ F such that N is unsatisfiable. The emerging viewpoint of MUSes as the root
  causes of unsatisfiability has led MUSes to find applications in a wide variety
  of diagnostic approaches. Recent advances in finding and enumeration of MUSes have
  motivated researchers to discover applications that can benefit from rich information
  about the set of MUSes. One such extension is that of counting the number of MUSes,
  which has shown to describe the inconsistency metrics for general propositional
  knowledge bases. The current best approach for MUS counting is to employ a MUS enumeration
  algorithm, which often does not scale for the cases with a reasonably large number
  of MUSes. Motivated by the success of hashing-based techniques in the context of
  model counting, we design the first approximate counting procedure with (epsilon,delta)
  guarantees, called AMUSIC. Our approach avoids exhaustive MUS enumeration by combining
  the classical technique of universal hashing with advances in QBF solvers along
  with a novel usage of union and intersection of MUSes to achieve runtime efficiency.
  Our prototype implementation of AMUSIC is shown to scale to instances that were
  clearly beyond the reach of enumeration-based approaches.
authors:
- Jaroslav Bendik
- Kuldeep S. Meel
date: 2020-05-18 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of 32nd International Conference on Computer-Aided Verification
  (CAV)*
publication_types:
- '1'
selected: true
title: Approximate Counting of Minimal Unsatisfiable Subsets
url_pdf: https://www.cs.toronto.edu/~meel/Papers/cav20-bm.pdf
---

