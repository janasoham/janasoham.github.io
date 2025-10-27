---
title: "Empirical Bayes via ERM and Rademacher complexities: the Poisson model"
collection: publications
permalink: /publications/COLT-erm
excerpt: ''
date: 2023-01-01
venue: 'Conference on Learning Theory'
citation: 'with Anzo Teh, Yury Polyanskiy and Yihong Wu'
topic: 'embayes'
paperurl: "https://arxiv.org/abs/2307.02070"

---

Abstract
========

We consider the problem of empirical Bayes estimation for (multivariate) Poisson means. Existing solutions that have
been shown theoretically optimal for minimizing the regret (excess risk over the Bayesian oracle that knows the prior) 
have several shortcomings. For example, the classical Robbins estimator does not retain the monotonicity property of
the Bayes estimator and performs poorly under moderate sample size. Estimators based on the minimum distance and non-parametric
maximum likelihood (NPMLE) methods correct these issues, but are computationally expensive with complexity growing exponentially
with dimension. Extending the approach of Barbehenn and Zhao (2022), in this work we construct monotone estimators based on
empirical risk minimization (ERM) that retain similar theoretical guarantees and can be computed much more efficiently. Adapting
the idea of offset Rademacher complexity Liang et al. (2015) to the non-standard loss and function class in empirical Bayes,
we show that the shape-constrained ERM estimator attains the minimax regret within constant factors in one dimension and within
logarithmic factors in multiple dimensions.
