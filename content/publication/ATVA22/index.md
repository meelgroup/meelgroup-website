---
abstract: "Given a system of constraints over a set $X$ of variables, projected model counting asks us to count satisfying assignments of the constraint system projected on a subset $P$ of $X$. A key idea used in modern projected counters is to first compute an <em>independent support</em>, say $I$, that is often a small subset of $P$, and to then count models projected on $I$ instead of on $P$. While this has been effective in scaling performance of counters, the question of whether we can benefit by projecting on variables beyond $P$ has not been explored. In this paper, we study this question and show that contrary to intuition, it can be beneficial to project on variables even beyond $P$. In several applications, a good upper bound of the projected model count often suffices. We show that in several such cases, we can identify a set of variables, called <em>upper bound support (UBS)</em>, that is not necessarily a subset of $P$, and yet counting models projected on UBS guarantees an upper bound of the projected model count. Theoretically, a UBS can be exponentially smaller than the smallest independent support. Our experiments show that even otherwise, UBS-based projected counting can be faster than independent support-based projected counting, while yielding bounds of high quality. Based on extensive experiments, we find that UBS-based projected counting can solve many problem instances that are beyond the reach of a state-of-the-art independent support-based projected model counter."
authors:
- Jiong Yang
- Supratik Chakraborty
- Kuldeep S. Meel
date: 2022-08-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *International Symposium on Automated Technology for Verification and Analysis (ATVA)*
publication_types:
- '1'
selected: true
title: 'Projected Model Counting: Beyond Independent Support'
url_pdf: files/publications/ATVA22.pdf
# url_dataset: 
url_code: https://github.com/meelgroup/arjun
# url_video: 
---

