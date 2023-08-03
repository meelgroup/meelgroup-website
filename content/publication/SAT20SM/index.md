---
abstract: 'CDCL-based SAT solvers have transformed the field of automated reasoning
  owing to their demonstrated efficiency at handling problems arising from diverse
  domains. The success of CDCL solvers is owed to the design of clever heuristics
  that enable the tight coupling of different components. One of the core components
  is phase selection, wherein the solver, during branching, decides the polarity of
  the branch to be explored for a given variable. Most of the state-of-the-art CDCL
  SAT solvers employ phase-saving as a phase selection heuristic, which was proposed
  to address the potential inefficiencies arising from far-backtracking. In light
  of the emergence of chronological backtracking in CDCL solvers, we re-examine the
  efficiency of phase saving. Our empirical evaluation leads to a surprising conclusion:
  The usage of phase saving and random selection of polarity during chronological
  backtracking leads to indistinguishable runtime performance in terms of instances
  solved and PAR-2 score. We introduce Decaying Polarity Score (DPS) to capture the
  trend of the polarities attained by the variable, and upon observing lack of performance
  improvement due to DPS, we turn to a more sophisticated heuristic seeking to capture
  the activity of literals and the trend of polarities: Literal State Independent
  Decaying Sum (LSIDS). We find the 2019 winning SAT solver, Maple_LCM_Dist_ChronoBTv3,
  augmented with LSIDS solves 6 more instances while achieving a reduction of over
  125 seconds in PAR-2 score, a significant improvement in the context of the SAT
  competition.'
authors:
- Arijit Shaw
- Kuldeep S. Meel
date: 2020-05-19 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications
  of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: Designing New Phase Selection Heuristics
url_code: https://github.com/meelgroup/duriansat
url_dataset: https://doi.org/10.5281/zenodo.3817476
url_pdf: https://www.cs.toronto.edu/~meel/Papers/sat20-sm.pdf
url_preprint: https://arxiv.org/abs/2005.04850
url_slides: files/slides/SAT20_arijit_LSIDS.pdf
url_video: https://www.youtube.com/watch?v=t646RnONNHE
---
