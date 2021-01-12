+++
widget = "blank"
date = 2016-04-20T00:00:00
draft = false
headless = true  # This file represents a page section.
active = true


# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "<center>Research</center>"
subtitle = ""

# Order that this section will appear in.
weight = 12

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

+++

# __Overview__

Broadly, our research group is focused on the development of a rigorous
mathematical framework for <b> provably verified, correct-by-construction,
explainable probabilistic reasoning systems </b> building on recent
breakthroughs in formal methods and symbolic reasoning; and deployment of our
algorithmic framework in the real world including applications in reliability
estimation of critical infrastructure and computational sustainability.

At a more technical level, we work at the intersection of formal methods and
artificial intelligence. We seek to develop formal methods for AI techniques and
also employ advances in AI techniques for the development of formal method
algorithmic and system frameworks.


## <u> Theme 1: Revisiting NP Revolution: New Paradigms for SAT/SMT/MaxSAT Solvers </u>

Two observations motivate this research theme:

O1: The success of SAT/SMT/MaxSAT solvers has allowed researchers to employ them
as "oracles" inside larger algorithmic components, which give rise to rich
structure in the queries to the SAT solvers, and

O2: Modern SAT/SMT solvers achieve scalability and robustness with sophisticated
heuristics that are challenging to understand and explain.

O1 necessitates design of solvers that can exploit the rich structures of
queries without losing the generality offered by CNF. Our recent work has
proposed new paradigms for CNF+XOR constraints [[aaai19]]({{<ref
"/publication/AAAI19_BIRD.md">}}) and CNF+ANF constraints [[date19]]({{<ref
"/publication/DATE_CSCM19.md">}}).

A consequence of O2 is that the development of new algorithmic insights has been
largely restricted to expert intuitions and evaluation of the new insights have
been restricted to performance measurement in terms of the runtime of solvers or
a proxy for the runtime of solvers. In this project, our focus is to enable
data-driven design and understanding of SAT Solvers. In particular, we view
modern conflict-driven clause learning (CDCL) solvers as a composition of
classifiers and regressors for different tasks such as branching, clause memory
management, and restarting. We will employ supervised learning and uses
extensive, multi-gigabyte data extracted from runs of a single SAT solver to
perform predictive analytics. Our [[SAT-19]]({{<ref
"/publication/SAT19_cball.md">}}) paper presents the first version of the
system, called CrystalBall, that we are building.



## <u> Theme 2: Constrained Sampling and Integration/Counting </u>

Constrained sampling and counting are two fundamental problems in data analysis.
In constrained sampling, the task is to sample randomly, subject to a given
weighting function, from the set of solutions to a set of given constraints
while for constrained counting, the task is to count the total weight, subject
to a given weighting function, of the set of solutions of the given constraints.
Both of these problems have applications in machine learning, probabilistic
reasoning, planning, hardware, and software testing, among other areas.

Our focus in on the development of new algorithmic techniques for constrained
sampling and counting, combining the classical technique of universal hashing
with advances in Boolean reasoning. Many of the ideas underlying the proposed
approach were go back to the 1980s, but they have never been reduced to
practice. Recent progress in Boolean reasoning is enabling us to reduce these
algorithmic ideas to practice and obtain breakthrough results in constrained
sampling and counting, providing a new algorithmic toolbox in design
verification, machine learning, probabilistic reasoning, and the like.

We are focused on

1. Algorithmic advances in sampling and counting [[aaai19]]({{<ref
   "/publication/AAAI19_BIRD.md">}}).
2. Application of sampling and counting to problems arising in different domains
   [[sat19]]({{<ref "/publication/SAT19_heu.md">}}) [[vmcai19]]({{<ref
   "/publication/VMCAI18.md">}}).
3. Revisiting theoretical foundations in light of existence of solvers but not
   oracles.


## <u> Theme 3: Verification of AI Systems </u>


The modern AI systems significantly differ from traditional systems in
their reliance on probabilistic reasoning.  Often statistical tests are
employed to argue for the accuracy/robustness of these systems, but such
statistical tests are usually performed on a tiny number of samples for
which no theoretical guarantees exist for their accuracy.

In contrast to testing for traditional hardware and software systems, where one trace is sufficient to prove the existence of a bug; such is not the case for samplers as one sample is typically not sufficient to prove non-conformity of the underlying systems. Our recent work [[aaai19]]({{<ref"/publication/AAAI19_testing.md">}}),[[neurips20]]({{<ref"https://meelgroup.github.io/publication/neurips20_testing">}}) showcased, to the best of our knowledge, the first algorithmic framework, Barbarik, to test whether the distribution generated by a sampler is close to an arbitrary weighted distribution.

In our [[ccs19]]({{<ref "/publication/CCS19.md">}}) we propose a quantitative
verification framework instantiated on binarized neural networks that allows
verification of robustness, fairness and trojan attack success properties. In
this framework, the user can quantify how often a given property is true.
However, often users are interested to bound the probability that a property is
true. To this end, in our [recent work](https://arxiv.org/abs/2002.06864) we propose a sound sampling-based
procedure called PROVERO and apply it to verify the robustness of deep neural
networks. We propose a new attack agnostic metric adversarial hardness to
capture model's robustness based on our procedure.


## <u> Theme 4: Interpretable and Actionable Explanations for AI Systems </u>

Interpretability has become a central thread in ML research. As ML algorithms
continue to permeate critical application domains such as medicine, legal, and
transportation, it becomes increasingly important to allow human domain experts
to understand and interact with ML solutions. Providing meaningful explanations
for automated decisions is an increasingly important task. In this research
theme, we are investigating techniques for two categories of explanations:

1. Interpretable explanations such as those specified using a small set of
   rules/formulas. In particular, we have designed a MaxSAT based formulation
   for learning interpretable rules in CNF/DNF [[cp18]]({{<ref
   "/publication/MM18.md">}}) and later extended this formulation by
   incorporating incremental learning of small rules [[aies19]]({{<ref
   "/publication/AIES19.md">}}). In the [[ecai20]]({{<ref
   "/publication/ECAI20.md">}}) paper we have proposed an efficient incremental
   learning procedure for learning classification rules in a more expressible
   Boolean representation, namely relaxed-CNF.


2. In settings where the cognitive burden of complete explanations is too high,
   people often do not seek to know why a particular event happened, but rather
   why an alternative one didn’t. Due to the heuristic nature of explanations
   produced by existing tools, it is necessary to validate them, and our
   approach applies the development in formal methods to aid validation. As an
   example, our recent work [[sat19]]({{<ref "/publication/SAT19_heu.md">}})
   proposed a counting-based method to assess the quality of explanations
   rigorously.

