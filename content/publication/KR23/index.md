---
abstract: "First-order model counting (FOMC) is a computational problem that asks to count the models of a sentence in finite-domain first-order logic. In this paper, we argue that the capabilities of FOMC algorithms to date are limited by their inability to express many types of recursive computations. To enable such computations, we relax the restrictions that typically accompany domain recursion and generalise the circuits used to express a solution to an FOMC problem to directed graphs that may contain cycles. To this end, we adapt the most well-established (weighted) FOMC algorithm ForcLift to work with such graphs and introduce new compilation rules that can create cycle-inducing edges that encode recursive function calls. These improvements allow the algorithm to find efficient solutions to counting problems that were previously beyond its reach, including those that cannot be solved efficiently by any other exact FOMC algorithm. We end with a few conjectures on what classes of instances could be domain-liftable as a result."
authors:
- Paulius Dilkas
- Vaishak Belle
date: 2023-06-09 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Principles of Knowledge Representation and Reasoning (KR)*
publication_types:
- '1'
selected: true
title: 'Synthesising Recursive Functions for First-Order Model Counting: Challenges, Progress, and Conjectures'
url_pdf: files/publications/kr23_fomc.pdf
url_code: https://github.com/dilkas/kr23-db
---
