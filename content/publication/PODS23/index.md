---
abstract: 'We consider the problem of computing the probability of a query over a tuple-independent probabilistic database, known as the probabilistic query evaluation (PQE) problem. The problem is well-known to be $\#\P$-hard in data complexity for conjunctive queries in general, as well as for several subclasses of conjunctive queries. Existing approximation approaches for dealing with hard queries have centred on computing the lineage of the query over the database, which can be intractable for all but the smallest of queries due to the exponential dependence of the lineage size on the query length.

In this paper, we take a first step towards bridging this gap, by showing how to construct a fully polynomial-time randomized approximation scheme (FPRAS) for the PQE problem for any class of self-join-free conjunctive queries of bounded hypertree width, that runs in time polynomial in both the query length and database instance size. An interesting consequence of our result is the existence of classes of queries that are $\#\P$-hard in data complexity to evaluate exactly, yet easy to approximate both in terms of query length and database size.'
authors:
- Timothy van Bremen
- Kuldeep S. Meel
date: 2023-06-18 00:00:00
highlight: true
image_preview: ''
math: true
publication: 'In *ACM Symposium on Principles of Database Systems (PODS)*'
publication_types:
- '1'
selected: true
title: 'Probabilistic Query Evaluation: The Combined FPRAS Landscape'
url_pdf: https://www.comp.nus.edu.sg/~tvanbr/papers/pods23.pdf
---