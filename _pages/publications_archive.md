---
layout: archive
title: "Research - Zhou"
permalink: /publication_old/
author_profile: false
redirect_from:
  - /research
  - /publications
---

{% include base_path %}

### Job Market Paper
Heterogeneous Treatment Effects under Complex Network Interference [draft forthcoming] [[code](https://github.com/lbz5158/network_rkhs)]
* *Abstract*: This paper develops a semiparametric method for estimating heterogeneous treatment effects under network interference. Extending the literature of linear-in-means models, we propose a novel framework that non-parametrically models individual-level treatment responses via functions in a reproducing kernel Hilbert space (RKHS) to capture flexible heterogeneity induced by covariates. The model accommodates both endogenous and contextual peer effects and addresses the reflection problem using an instrumental variables (IV) strategy that leverage higher order neighbors across the network graph. A fixed-point iterative algorithm estimates the parameters and the function jointly. The paper derives identification conditions, establishes asymptotic properties of the estimators, and provides convergence guarantees for the algorithm.  Monte Carlo simulation highlights the method’s performance and easy implementability even when the dimensionality of covariates becomes large relative to the sample size. We revisit the social network experiment in Cai et al. (2015) and apply our procedure to recover the non-linear relation between insurance knowledge score and the explanatory variables in the study.

### Working Paper
Efficient Computation of Confidence Sets Using Classification on Equidistributed Grids [[draft](https://arxiv.org/pdf/2401.01804)] [[code](https://github.com/lbz5158/svm_equidistribution)]

* *Abstract*: Economic models produce moment inequalities, which can be used to form tests of the true parameters. Confidence sets (CS) of the true parameters are derived by inverting these tests. However, they often lack analytical expressions, necessitating a grid search to obtain the CS numerically by retaining the grid points that pass the test. When the statistic is not asymptotically pivotal, constructing the critical value for each grid point in the parameter space adds to the computational burden. In this paper, we convert the computational issue into a classification problem by using a support vector machine (SVM) classifier. Its decision function provides a faster and more systematic way of dividing the parameter space into two regions: inside vs. outside of the confidence set. We label those points in the CS as 1 and those outside as -1. Researchers can train the SVM classifier on a grid of manageable size and use it to determine whether points on denser grids are in the CS or not. We establish certain conditions for the grid so that there is a tuning that allows us to asymptotically reproduce the test in the CS. This means that in the limit, a point is classified as belonging to the confidence set if and only if it is labeled as 1 by the SVM.



### Work in Progress
The Impact of Short-Term Rental on Local Housing Markets: Evidence from Mexico, with Armando R. Colina.
* *Abstract*: Recent years have seen some sizable increase in consumer prices in Mexico. Statistics show that housing prices have risen to become the second largest contributor to the inflation over the
past few years next to food expenditure. Recent literature mainly focuses on the effects of financialization and gentrification. In this paper, we aim to investigate the role of one other important
factor in the rising prices of the local housing markets, short-term rental listings. We propose to use detailed Airbnb data along with national data on credit taken to purchase real estate properties
as well as data from some other public sources to quantitatively analyze the impact, namely the direct and the spillover effects, of new Airbnb listings on the prices of the neighboring real estate
properties. We employ a novel network interference model to disentangle the spillover effect from the direct effect and provide semiparametric consistent estimates of the effects.

Online Causal Learning and Treatment Assignment in Networks, with Yubai Yuan.
