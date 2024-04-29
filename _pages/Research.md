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
    **Abstract:** This study analyzes an identification and estimation procedure for the causal treatment effect, explicitly considering network changes resulting from treatment. Compared to the classical approach in program evaluation literature that assumes independent units, recent empirical studies emphasize the significance of spillover effects. However, these studies often assume that the underlying network is fixed or unaffected by treatment. At the same time, there has been some empirical evidence that treatment can also affect the network. This study analyzes the identification of the causal effect of treatment with interference between units and also accounts for possible network changes. The main contribution of this study is the decomposition of the causal effect into two distinct parts: the effect of treatment when the network remains unchanged and the effect when only the network structure is changed by the treatment. This approach enhances our understanding of the mechanisms of a policy or program by explicitly considering counterfactual scenarios in which the network is changed or unchanged due to treatment. Additionally, the study addresses quasi-experimental situations, providing a Difference-in-Differences approach.

* “Local Average Treatment Effects with Imperfect Compliance and Interference”
  ---
    **Abstract:** This study addresses the identification and estimation of causal effects in scenarios where units interact and imperfect compliance is present. In cases where treatment take-up is endogenous due to imperfect compliance, the standard solution is to use the treatment assignments as instruments for the treatment take-up to identify the local average treatment effects (LATE). The key assumption for identifying LATE is monotonicity in potential treatments. This paper extends this approach to situations involving the interaction of two units by introducing a weak concept of monotonicity that is a generalization of the restrictions on the potential treatment, such as monotonicity and one-sided noncompliance. Under the weak monotonicity, this study proposes a general identification result in this setting, provided that additional exclusion restrictions for the compliance patterns exist. This identification can be applied to situations where traditional assumptions may not be fully satisfied. A two-stage estimator for the identified parameters is introduced, with its properties evaluated through simulation studies. The proposed method is illustrated by real-world data from a randomized experiment that provided access to a savings account.

    * **Data and Codes:**
      * Data Source: 
      * Estimation Package: [Stata, Matlab, Python, Julia, R]
      * Simulation: [[Matlab]](https://github.com/SiwonRyu/3YP_Simulation)
      * Empirical Application: [Stata]

* “Direct and Indirect Treatment Effects with Social Interaction”
  ---
    **Abstract:** This study analyzes identifications and estimations in the presence of social interactions. The potential outcomes are functions of own treatment status and exposures, and the exposure is a function of neighbors’ treatment status. If the distribution of exposures is determined by own treatment status, the treatment effect can be decomposed into direct and indirect effects using an approach mediation model. Suppose the exposure distribution is from the underlying random graph of the social network. Then, it can be interpreted as the treatment has indirect effects by changing the underlying network structure. Therefore, the exposures play the role of mediator, and the variation of the mediator due to the treatment status identifies the direct and indirect treatment effects separately. Monte-Carlo  imulation studies and the empirical application of the impact of co-educated high school on academic performance show the proposed estimators and decompositions work well.


<div style="margin-top: 50px;">
</div>
Work in progress
======
* 