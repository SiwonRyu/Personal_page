---
layout: splash
title: ""
permalink: /research/
author_profile: true
---

<div style="margin-top: 100px;">
</div>


Working Papers
======
* “Decomposition of Causal Effect Accounting for Network Change” (Job market paper) 
  ---
    **Abstract:** This study analyzes the identification and estimation of treatment effects, explicitly considering network changes resulting from the treatment. Compared to the classical literature that assumes independent units, recent studies emphasize the significance of spillover effects. However, these studies often assume that the underlying network is fixed or unaffected by treatment. Meanwhile, there is empirical evidence suggesting that treatment can also affect the network. The purpose of this study is to estimate the causal treatment and spillover effects accounting for the causal network changes from the treatment. The main contribution of this study is the decomposition of the causal effects into two distinct parts: the effect of treatment when the network remains unchanged and the effect when only the network structure is changed by the treatment. This approach enhances our understanding of the mechanisms of a policy or program by considering counterfactual scenarios in which the network is changed or unchanged due to treatment. Additionally, the study addresses quasi-experimental situations, providing a Difference-in-Differences approach.	

  * Latest Version: [[Pdf]](/assets/docs/JMP.pdf)

* “Local Average Treatment Effects with Imperfect Compliance and Interference”
  ---
    **Abstract:** This study addresses the identification and estimation of causal effects in scenarios where units interact and imperfect compliance is present. When treatment take-up is endogenous due to imperfect compliance, the common solution is to use treatment assignments as instruments for the treatment take-up to identify the local average treatment effects (LATE). The key assumption for identifying LATE is monotonicity in potential treatments. This paper extends this approach to situations involving the interaction of two units by introducing a weak concept of monotonicity, which generalizes the ordering on potential treatment, such as monotonicity and one-sided noncompliance. Under this weak monotonicity, I show that the direct and indirect effects can be identified in this setting if there are additional exclusion restrictions for the compliance patterns. The resulting estimands remain valid even when traditional assumptions are all violated. I propose an estimating procedure for the treatment effects and evaluate its properties through Monte Carlo studies. Additionally, I illustrate the proposed method using an experimental study in Kenya that provided access to a savings account.

  * Latest Version: [[Pdf]](/assets/docs/3YP.pdf)
  * Data Source: [[Replication Data]](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/WBD2QD)
    * Dupas, Pascaline; Keats, Anthony; Robinson, Jonathan, 2017, "The Effect of Savings Accounts on Interpersonal Financial Relationships: Evidence from a Field Experiment in Rural Kenya", https://doi.org/10.7910/DVN/WBD2QD, Harvard Dataverse, V1
  * Estimation Package: [[Stata, Matlab]](https://github.com/SiwonRyu/LATEs_Estimation)
  * Simulation: [[Matlab]](https://github.com/SiwonRyu/LATEs_Simulation)
  * Empirical Application: [[Stata, Matlab]](https://github.com/SiwonRyu/LATEs_Empirical)

* “Direct and Indirect Treatment Effects with Social Interaction”
  ---
    **Abstract:** This study investigates the identification and estimation of treatment effects when units interact with each other through a network, and the underlying network is also influenced by the treatment. Outcomes are determined not only by their own treatment but also by others' treatments through some statistics, such as the number of treated friends. These statistics are often called exposure, and are generally determined by both the treatment of others and the underlying network structure. If the network is influenced by treatment, then one's own treatment affects the outcome both directly and indirectly by altering the network. In this scenario, exposure acts as a mediator for the treatment, and thus the variation in the exposure distribution identifies direct and indirect causal effects through a mediation model. I propose a nonparametric estimator, demonstrate its performance using Monte Carlo simulations, and apply it to an empirical study examining the impact of co-education in high schools on academic performance to illustrate the proposed estimator and its decomposition.

  * Latest Version: [[Pdf]](/assets/docs/2YP.pdf)
  * Data Source: [[Korean Education & Employment Panel Survey (KEEP II)]](https://www.krivet.re.kr/eng/eu/eg/euCAADs.jsp) (from Korea Research Institute for Vocational Education & Training)

<!--
  * Estimation Package: [Stata, Matlab, Python, Julia, R]
  * Simulation: [[Matlab]](https://github.com/SiwonRyu/3YP_Simulation)
  * Empirical Application: [Stata]
-->

<div style="margin-top: 100px;">
</div>

Work in progress
======
* “Heterogeneous Parental Labor Supply Responses to Children’s Severe Health Shocks: Evidence from Administrative Data from South Korea (with Jungmin Lee and Hyuncheol Bryant Kim)”
  ---
  **Abstract:** This study examines the impact of a child's cancer diagnosis on parents' labor supply. Using data from South Korea's National Health Insurance System, we find heterogeneous effects based on gender, parents' relative income, and employment type. Specifically, we observe that mothers experience a significant decline in employment and income following their child's cancer diagnosis, while fathers' employment and income remain relatively unchanged. The decrease in fathers' labor supply is only observed among those with lower income compared to their spouse, whereas mothers' employment decreases regardless of relative income. Furthermore, we find that self-employed mothers are less affected compared to wage workers, while the effects on fathers are generally minimal.
