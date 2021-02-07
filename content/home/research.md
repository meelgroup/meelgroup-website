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
## Enabling Beyond NP Revolution


<p style=text-align:justify>
My research program’s long-term vision is to advance automated reasoning techniques to enable computing to deal with increasingly uncertain real-world environments. From the core technical perspective, my research program is motivated by the unprecedented advances in the combinatorial solving techniques over the past three decades, often called as $NP$ $revolution$, owing to the focus on the fundamental problem in Nondeterministic Polynomial (NP) time complexity: satisfiability (SAT). The NP revolution offers us the opportunity to develop scalable techniques for problems that lie $Beyond$ $NP$. In particular, I focus on four fundamental problems that lie beyond NP: constrained counting, constrained sampling, functional synthesis, and maximum satisfiability. My research program is focused on enabling $Beyond$ $NP$ Revolution via making progress on the following critical enabling ingredients:
</p>


## <u> Theme 1: Beyond Worst-Case Algorithmic Design </u>


<p style=text-align:justify>
While theoreticians have studied the aforementioned problems for
over thirty years, such studies employed the narrow lens of SAT oracles, which did not broadly allow a more
nuanced characterization of the SAT queries’ complexity. In contrast, we focus on designing algorithms with
SAT queries that can be efficiently solved by the underlying SAT solvers. In the context of approximate counting, we have developed a hashing-based framework, ApproxMC, that relies on sparse XORs to circumvent the
practical hardness of queries based on dense XORs [<a href="/publication/cp18">MSV19a</a>, <a href="/publication/ijcai19_dnfcounter">MSV19b</a>, <a href="/publication/sat20abm">ABM20</a>, <a href="/publication/lics-20-am">MA20</a>, <a href="/publication/cav20bm">BM20</a>]. The LICS20 paper [<a href="/publication/lics-20-am">MA20</a>](co-authored with S. Akshay) resolved the longstanding open problem of designing a sparse XOR-based algorithmic framework that can achieve runtime improvement without losing theoretical guarantees. As a high degree of symmetry in the underlying constraints amplifies the practical hardness, we rely on domainlevel symmetry breaking for performance improvement [<a href="/publication/tacas20wuawmk">WUA+20</a>]. In the context of sampling, our framework, Waps, employs the progress in knowledge compilation to achieve scalability without losing theoretical guarantees [<a href="/publication/lpar18">SGRM18</a>, <a href="/publication/tacas19">GSRM19</a>]. In follow-up work, we improved the underlying algorithmic framework for knowledge compilation via probabilistic caching enabled via universal hashing [<a href="/publication/ijcai19_ganak">SRSM19</a>]. Building on the success of constrained sampling and machine learning techniques, we proposed a novel algorithmic framework, called Manthan, for functional synthesis that achieved significant breakthrough in the number of instances solved [<a href="/publication/cav20_manthan">GRM20a</a>].
</p>


## <u> Theme 2: Applications </u>


<p style=text-align:justify>
A key ingredient in the NP revolution was focus on the instances arising from the real-world, allowing the design of techniques tuned to practical instances. In a similar vein, we focus on discovering new applications for the aforementioned problems and the design of efficient modeling schemes. In an interdisciplinary collaboration, we reduced the problem of reliability of power transmission grids to constrained counting [<a href="/publication/ress">PDOMV19</a>]. Furthermore, we reduce the quantitative verification of neural networks [<a href="/publication/sat19_heu">NSM+19</a>, <a href="/publication/ccs19">BSS+19</a>], and quantification of information flow [<a href="/publication/vmcai18">BEH+18</a>] to constrained counting. Building on our algorithmic progress in constrained sampling, we design efficient technique for higher $t$-wise coverage in the context of highly configurable software systems [<a href="https://www.comp.nus.edu.sg/~meel/Papers/fse20blm.pdf">BLM20</a>]. In regards to maximum satisfiability, we showed that the problem of decoding in group testing reduces to maximum satisfiability [<a href="/publication/aaai20">CGSM20</a>]. In another line of work, we design efficient provable techniques for learning interpretable classifiers via reduction to MaxSAT [<a href="/publication/mm18">MM18</a>, <a href="/publication/aies19">GM19</a>, <a href="/publication/ecai20">GMM20</a>].
</p>


## <u> Theme 3: Query-Driven Design of Solvers </u>


<p style=text-align:justify>
SAT solvers’ usage inside broader algorithmic frameworks gives rise to the rich structure of the SAT queries. We have taken a twofold approach: On one hand, our recent work on uncovering the structure of solution spaces through the lens of phase transition behavior [<a href="/publication/ijcai19_cardxor">PJM19</a>, <a href="/publication/cp20">GRM20b</a>]. As a next step, we focus on engineering the underlying architecture of the SAT solvers. Given the crucial importance of CNF-XOR solving for counting and sampling, we have proposed a novel architecture, BIRD, relying on the tight integration of CDCL and Gauss-Jordan Elimination to achieve significant improvements for CNF-XOR solving [<a href="/publication/aaai19_bird">SM19</a>, <a href="/publication/cav20sgm">SGM20</a>]. Motivated by applications in cryptography and collaboration with the Defense Service Organization (DSO), we developed a new architecture, Bosphorus, for CNF-ANF formulas [<a href="/publication/date_cscm19">CSCM19</a>], and further improved performance with phase saving [<a href="/publication/sat20sm">SM20</a>]. Our most ambitious project, CrystalBall [<a href="/publication/sat19_cball">SKM19</a>], focuses on the data-driven synthesis of SAT Solvers by combining the advances in proof systems with supervised learning.
</p>


## <u> Theme 4: Testing Framework </u>


<p style=text-align:justify>
Similar to the pivotal role played by testing frameworks in the $NP$ $revolution$, the realization of the Beyond NP revolution would need scalable testing and verification methodologies. As a first step, we have focused on testing of constrained samplers. In contrast to conventional programs, one trace/sample is typically inadequate to prove the non-conformity of the underlying samplers. We are developing an algorithmic framework, Barbarik, that sits at the intersection of property testing and symbolic reasoning [<a href="/publication/aaai19_testing">CM19</a>]. Barbarik [<a href="/publication/aaai19_testing">CM19</a>, <a href="/publication/neurips20_testing">MPC20</a>] can handle product distributions and is the first tester to require a constant number of samples, in contrast to prior work requiring exponentially many samples.
</p>


## <u> Open-Source Tools </u>


<p style=text-align:justify>
Our research has led to the release of 10 actively maintained <a href="https://meelgroup.github.io/#projects"> open source tools </a>. Our SAT solver entry won 3rd place in the Main Track of the highly prestigious and competitive SAT competition 2020 (the first instance of a top-3 finish by an entry from Singapore) while our model counting entry won 1st place in two of three tracks.
</p>
