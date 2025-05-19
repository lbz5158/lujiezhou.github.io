---
layout: archive
title: ""
permalink: /research/
author_profile: false
redirect_from:
  - /research
  - /publications
---

{% include base_path %}

### Job Market Paper
Heterogeneous Treatment Effects under Complex Network Interference [[code]](https://github.com/lbz5158/network_rkhs)
* Draft forthcoming. 

### Working Paper
Efficient Computation of Confidence Sets Using Classification on Equidistributed Grids [[pdf]](https://arxiv.org/abs/2401.01804) [[code]](https://github.com/lbz5158/svm_equidistribution)

* Abstract: Economic models produce moment inequalities, which can be used to form tests of the true parameters. Confidence sets (CS) of the true parameters are derived by inverting these tests. However, they often lack analytical expressions, necessitating a grid search to obtain the CS numerically by retaining the grid points that pass the test. When the statistic is not asymptotically pivotal, constructing the critical value for each grid point in the parameter space adds to the computational burden. In this paper, we convert the computational issue into a classification problem by using a support vector machine (SVM) classifier. Its decision function provides a faster and more systematic way of dividing the parameter space into two regions: inside vs. outside of the confidence set. We label those points in the CS as 1 and those outside as -1. Researchers can train the SVM classifier on a grid of manageable size and use it to determine whether points on denser grids are in the CS or not. We establish certain conditions for the grid so that there is a tuning that allows us to asymptotically reproduce the test in the CS. This means that in the limit, a point is classified as belonging to the confidence set if and only if it is labeled as 1 by the SVM.



### Work in Progress
Colina, A. R. and L. Zhou (2024): “The Impact of Short-Term Rental on Local Housing Markets:
Evidence from Mexico,” Banco de México working papers.
* Abstract: Recent years have seen some sizable increase in consumer prices in Mexico. Statistics show that housing prices have risen to become the second largest contributor to the inflation over the
past few years next to food expenditure. Recent literature mainly focuses on the effects of financialization and gentrification. In this paper, we aim to investigate the role of one other important
factor in the rising prices of the local housing markets, short-term rental listings. We propose to use detailed Airbnb data along with national data on credit taken to purchase real estate properties
as well as data from some other public sources to quantitatively analyze the impact, namely the direct and the spillover effects, of new Airbnb listings on the prices of the neighboring real estate
properties. We employ a novel network interference model to disentangle the spillover effect from the direct effect and provide semiparametric consistent estimates of the effects.

Yuan, Y. and L. Zhou (2023): “Online Causal Learning and Treatment Assignment in Networks.”
