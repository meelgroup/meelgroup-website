---
abstract: 'Answer Set Programming (ASP) is a framework in artificial intelligence and knowledge representation for 
declarative modeling and problem solving. Modern ASP solvers focus on the
computation or enumeration of answer sets. However, a variety
of probabilistic applications in reasoning or logic programming require counting answer sets. While counting can be
done by enumeration, simple enumeration becomes immediately infeasible if the number of solutions is high. On the other
hand, approaches to exact counting are of high worst-case
complexity. In fact, in propositional model counting, exact
counting becomes impractical. In this work, we present a scalable approach to approximate counting for ASP. Our approach
is based on systematically adding parity (XOR) constraints to
ASP programs, which divide the search space. We prove that
adding random XOR constraints partitions the answer sets of
an ASP program. In practice, we use a Gaussian eliminationbased approach by lifting ideas from SAT to ASP and integrate
it into a state of the art ASP solver, which we call ApproxASP.
Finally, our experimental evaluation shows the scalability of
our approach over existing ASP systems.'
authors:
- Mohimenul Kabir
- Flavio Everardo
- Ankit Shukla
- Johannes K. Fichte
- Markus Hecher
- Kuldeep S. Meel
date: 2022-06-09 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of AAAI Conference on Artificial Intelligence (AAAI)*
publication_types:
- '1'
selected: true
title: 'ApproxASP – A Scalable Approximate Answer Set Counter'
url_code: https://github.com/meelgroup/approxasp2
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/aaai22-keskhm.pdf
---

