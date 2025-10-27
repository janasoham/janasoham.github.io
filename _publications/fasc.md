---
title: "Factor Adjusted Spectral Clustering for Mixture Models"
collection: publications
permalink: /publications/fasc
excerpt: ''
date: 2024-01-08
venue: 'Preprint'
topic: 'clustering'
citation: 'with Shange Tang and Jianqing Fan'

paperurl: "https://janasoham.github.io/files/fasc.pdf"

---

Abstract
========

This paper studies a factor modeling-based approach for clustering high-dimensional data generated from a mixture of strongly correlated variables. Statistical modeling with correlated structures pervades modern applications in economics, finance, genomics, wireless sensing, etc., with factor modeling being one of the popular techniques for explaining the common dependence. Standard techniques for clustering high-dimensional data, e.g., naive spectral clustering, often fail to yield insightful results as their performances heavily depend on the mixture components having a weakly correlated structure. To address the clustering problem in the presence of a latent factor model, we propose the Factor Adjusted Spectral Clustering (FASC) algorithm, which uses an additional data denoising step via eliminating the factor component to cope with the data dependency. We prove this method achieves an exponentially low mislabeling rate, with respect to the signal to noise ratio under a general set of assumptions. Our assumption bridges many classical factor models in the literature, such as the pervasive factor model, the weak factor model, and the sparse factor model. The FASC algorithm is also computationally efficient, requiring only near-linear sample complexity with respect to the data dimension. We also show the applicability of the FASC algorithm with real data experiments and numerical studies, and establish that FASC provides significant results in many cases where traditional spectral clustering fails.
