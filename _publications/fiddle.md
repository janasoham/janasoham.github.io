---
title: "Factor Informed Double Deep Learning For Average Treatment Effect Estimation"
collection: publications
permalink: /publications/fiddle
excerpt: ''
date: 2025-01-08
venue: 'Preprint'
topic: 'deep_learning'
citation: 'with Jianqing Fan, Sanjeev Kulkarni, and Qishuo Yin'

paperurl: "https://janasoham.github.io/files/fiddle.pdf"

---

Abstract
========

We investigate the problem of estimating the average treatment effect (ATE) under a very general setup where the covariates can be high-dimensional, highly correlated, and can have sparse nonlinear effects on the propensity and outcome models. We present the use of a Double Deep Learning strategy for estimation, which involves combining recently developed factor-augmented deep learning-based estimators, FAST-NN, for both the response functions and propensity scores to achieve our goal. By using FAST-NN, our method can select variables that contribute to propensity and outcome models in a completely nonparametric and algorithmic manner and adaptively learn low-dimensional function structures through neural networks. Our proposed novel estimator, FIDDLE (Factor Informed Double Deep Learning Estimator), estimates ATE based on the framework of augmented inverse propensity weighting AIPW with the FAST-NN-based response and propensity estimates. FIDDLE consistently estimates
ATE even under model misspecification, and is flexible to also allow for low-dimensional covariates. Our method achieves semiparametric efficiency under a very flexible family of propensity and outcome models. We present extensive numerical studies on synthetic and real datasets to support our theoretical guarantees and establish the advantages of our methods over other traditional choices, especially when the data dimension is large.
