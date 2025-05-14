---
title: "Efficient Computation of Confidence Sets Using Classification on Equidistributed Grids
"
collection: publications
category: working paper
permalink: /publication/svm
excerpt: ''
date: 2024
venue: 'arXiv'
slidesurl: ''
paperurl: 'https://arxiv.org/abs/2401.01804'
bibtexurl: ''
citation: ''
---
Abstract: Economic models produce moment inequalities, which can be used to form tests of the true parameters. Confidence sets (CS) of the true parameters are derived by inverting these tests. However, they often lack analytical expressions, necessitating a grid search to obtain the CS numerically by retaining the grid points that pass the test. When the statistic is not asymptotically pivotal, constructing the critical value for each grid point in the parameter space adds to the computational burden. In this paper, we convert the computational issue into a classification problem by using a support vector machine (SVM) classifier. Its decision function provides a faster and more systematic way of dividing the parameter space into two regions: inside vs. outside of the confidence set. We label those points in the CS as 1 and those outside as -1. Researchers can train the SVM classifier on a grid of manageable size and use it to determine whether points on denser grids are in the CS or not. We establish certain conditions for the grid so that there is a tuning that allows us to asymptotically reproduce the test in the CS. This means that in the limit, a point is classified as belonging to the confidence set if and only if it is labeled as 1 by the SVM.

