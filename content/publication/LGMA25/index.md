---
title: 'Solution-Aware Vs Global ReLU Selection: Partial MILP Strikes Back for DNN Verification'
authors:
- Yuke Liao
- Blaise Genest
- Kuldeep S. Meel
- Shaan Aryaman
date: '2025-01-01T00:00:00'
publication: In *Proceedings of International Symposium on Automated Technology for Verification and Analysis (ATVA)*
publication_types:
- '1'
featured: false
math: true
abstract: 'To handle complex instances, we revisit a divide-and-conquer approach to break down the complexity: instead of few complex BaB calls, we rely on many small partial MILP calls. The crucial step is to select very few but very important ReLUs to treat using (costly) binary variables. The previous attempts were suboptimal in that respect. To select these important ReLU variables, we propose a novel solution-aware ReLU scoring (SAS), as well as adapt the BaB-SR and BaB-FSB branching functions as global ReLU scoring (GS) functions. We compare them theoretically as well as experimentally, and SAS is more efficient at selecting a set of variables to open using binary variables. Compared with previous attempts, SAS reduces the number of binary variables by around 6 times, while maintaining the same level of accuracy. Implemented in Hybrid MILP, calling first alpha,beta-CROWN with a short time-out to solve easier instances, and then partial MILP, produces a very accurate yet efficient verifier,
  reducing by up to 40% the number of undecided instances to low levels (8-15%), while keeping a reasonable runtime (46s-417s on average per instance), even for fairly large CNNs with 2 million parameters.'
url_pdf: https://arxiv.org/pdf/2507.23197
tags:
- Formal Methods 4 ML
---
