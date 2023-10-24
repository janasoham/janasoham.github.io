---
title: "Optimal prediction of Markov chains with and without spectral gap"

collection: publications
permalink: /publications/markov_prediction1
venue: 'NeurIPS, 2021. Longer version in IEEE Transactions on Information Theory'

date: 2023-01-01

excerpt: ""

paperurl: "https://arxiv.org/abs/2106.13947"

citation: "with Yanjun Han and Yihong Wu"

---

Abstract
========

We study the following learning problem with dependent data: Observing a trajectory of length $n$ from a stationary Markov chain with $k$ states, the goal is to predict the next state.
For  $3 \leq k \leq O(\sqrt{n})$, using techniques from universal compression, the optimal prediction risk in Kullback-Leibler divergence is shown to be $\Theta(\frac{k^2}{n}\log \frac{n}{k^2})$, in contrast to the optimal rate of $\Theta(\frac{\log \log n}{n})$ for $k=2$ previously shown in Falahatgar et. al. 2016. These rates, slower than the parametric rate of $O(\frac{k^2}{n})$, can be attributed to the memory in the data, as the spectral gap of the Markov chain can be arbitrarily small. To quantify the memory effect, we study irreducible reversible chains with a prescribed spectral gap. In addition to characterizing the optimal prediction risk for two states, we show that, as long as the spectral gap is not excessively small, the prediction risk in the Markov model is $O(\frac{k^2}{n})$, which coincides with that of an iid model with the same number of parameters. Extensions to higher-order Markov chains are obtained.



