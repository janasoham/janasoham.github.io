---
title: "Adversarially robust clustering with optimality guarantees"
collection: publications
permalink: /publications/median-clustering
excerpt: ''
date: 2023-01-01
venue: 'Accepted, IEEE Transactions on Information Theory'
topic: 'clustering'
citation: 'with Kun Yang and Sanjeev Kulkarni'

paperurl: "https://arxiv.org/abs/2306.09977"

---

Abstract
========

We consider the problem of clustering data points coming from sub-Gaussian mixtures.
Existing methods that provably achieve the optimal mislabeling error, such as the 
Lloyd algorithm, are usually vulnerable to outliers. In contrast, clustering methods
seemingly robust to adversarial perturbations are not known to satisfy the optimal 
statistical guarantees. We propose a simple algorithm that obtains the optimal
mislabeling rate even when we allow adversarial outliers to be present. Our algorithm
achieves the optimal error rate in constant iterations when a weak initialization
condition is satisfied. In the absence of outliers, in fixed dimensions, our theoretical
guarantees are similar to that of the Lloyd algorithm. Extensive experiments on various
simulated data sets are conducted to support the theoretical guarantees of our method.
