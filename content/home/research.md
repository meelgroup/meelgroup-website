+++
title = "Research"
date = 2016-04-20T00:00:00
draft = false
active = true


# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
subtitle = ""

# Order that this section will appear in.
weight = 6

+++

# __Overview__ 

Broadly, our research group is focused on the development of a rigorous mathematical framework for <b> provably verified, correct-by-construction, explainable probabilistic reasoning systems </b> building on recent breakthroughs in formal methods and symbolic reasoning; and deployment of our algorithmic framework in the real world including applications in reliability estimation of critical infrastructure and computational sustainability. On a more technical level, we work at the intersection of formal methods and artificial intelligence. We seek to develop formal methods for AI techniques and also employ advances in AI techniques for development of formal method algorithmic and system frameworks. 


## <u> Theme 1: Revisiting NP Revolution: New Paradigms for SAT/SMT/MaxSAT Solvers </u>

This research theme is motivated by two observations:

1. O1: The success of SAT/SMT/MaxSAT solvers has allowed researchers to employ them as "oracles" inside larger algorithmic components, which give rise to rich structure in the queries to the SAT solvers, and
2. O2: Modern SAT/SMT solvers achieve scalability and robustness with complex heuristics that are challenging to understand and explain. 

O1 necessitates design of solvers that can exploit the rich structures of queries without losing the generality offered by CNF. Our recent work has proposed new paradigms for CNF+XOR constraints
[[aaai19]]({{<ref "/publication/AAAI19_BIRD.md">}}) and CNF+ANF constraints [[date19]]({{<ref "/publication/date-cscm19.md">}}). 

A consequence of O2 is that the development of new algorithmic insights has been largely restricted to expert intuitions and evaluation of the new insights have been restricted to performance measurement in terms of the runtime of solvers or a proxy for the runtime of solvers. In this project, our focus is to enable data-driven design and understanding of SAT Solvers. In particular, we view modern conflict-driven clause learning (CDCL) solvers as a composition of classifiers and regressors for different tasks such as branching, clause memory management, and restarting. We  will employ supervised learning and uses extensive, multi-gigabyte data extracted from runs of a single SAT solver to perform predictive analytics. Our [[SAT-19]]({{<ref "/publication/sat19_cball.md">}}) paper presents the first version of the system, called CrystalBall, that we are building. 

 

## <u> Theme 2: Beyond NP Revolution: Constrained Sampling and Integration/Counting </u>

Constrained sampling and counting are two fundamental problems in data analysis. In constrained sampling the task is to sample randomly, subject to a given weighting function, from the set of solutions to a set of given constraints. This problem has numerous applications, including probabilistic reasoning, machine learning, statistical physics, and constrained-random verification. A related problem is that of constrained counting, where the task is to count the total weight, subject to a given weighting function, of the set of solutions of the given constraints. This problem has applications in machine learning, probabilistic reasoning, and planning, among other areas. Both problems can be viewed as aspects of one of the most fundamental problems in artificial intelligence, which is to understand the structure of the solution space of a given set of constraints. This work focuses on the development of new algorithmic techniques for constrained sampling and counting, based on a universal hashing -- a classical algorithmic technique in theoretical computer science. Many of the ideas underlying the proposed approach were go back to the 1980s, but they have never been reduced to practice. Recent progress in Boolean reasoning is enabling us to reduce these algorithmic ideas to practice, and obtain breakthrough results in constrained sampling and counting, providing a new algorithmic toolbox in design verification, machine learning, probabilistic reasoning, and the like. 

We are focused on

1. Algorithmic advances in sampling and counting.
2. Application of sampling and counting to problems arising in different domains.
3. Revisiting theoretical foundations in light of existence of solvers but not oracles. 


## <u> Theme 3: Verification of AI Systems </u>

The unprecedented advances in the machine learning techniques have led to a proliferation of Artificial Intelligence(AI)-based devices in our day to day life. The AI-based tools are increasingly employed to make consequential decisions for human subjects, in areas such as credit lending, policing, criminal justice, and medicine. Decisions made by these AI-based predictive models often have a long-lasting impact on people's lives. As such there is a strong need for the development of methodology for verification of AI systems. 

The modern AI systems significantly differ from traditional systems in their reliance on probabilistic reasoning.  Often statistical tests are employed to argue for the accuracy/robustness of these systems, but such statistical tests are usually performed on a tiny number of samples for which no theoretical guarantees exist for their accuracy. In contrast to testing for traditional hardware and software systems, where one trace is sufficient to prove the existence of a bug; such is not the case for samplers as one sample is typically not sufficient to prove non-conformity of the underlying systems. 


## <u> Theme 4: Interpretable and Explainable Explanations for AI Systems </u>

Interpretability has become a central thread in ML research. As ML algorithms
continue to permeate critical application domains such as medicine, legal, and
transportation, it becomes increasingly important to allow human domain experts to
understand and interact with ML solutions. Providing meaningful explanations for automated
decisions is an increasingly important task. In this research theme, we are investigating techniques for two categories of explanations:

1. Interpretable explanations such as those specified using small set of rules/formulas [[cp18]]({{<ref "/publication/mm18.md">}}) [[aies19]]({{<ref "/publication/aies19.md">}}) , and
2. In settings where the cognitive burden of complete explanations is too high, people often do not seek to know why
a particular event happened, but rather why an alternative one
didn’t . Providing a satisfactory answer to such
contrastive questions is often much easier than giving a full
causal path leading to the realized outcome. 

