---
title: "Extrapolating the profile of a finite population"
collection: publications
permalink: /publications/COLT-urn
excerpt: 'We find out minimax rate of estimating profile of a finite population in certain small sample regime. 
Our method involves characterizing both upper and lower bounds via an infinite dimensional optimization problem
based on Wolfowitz minimum distance estimators.'
date: 2020-01-01
venue: 'Conference on Learning Theory'
citation: 'with Yury Polyanskiy and Yihong Wu'

paperurl: "https://arxiv.org/abs/2005.10561"

---

Abstract
========

We study a prototypical problem in empirical Bayes. Namely, 
consider a population consisting of $k$ individuals each belonging to one of $k$ types (some types can be empty). 
Without any structural restrictions, it is impossible to learn the composition of the full population having observed only a small (random) subsample of size $m = o(k)$. 
Nevertheless, we show that in the sublinear regime of $m =\omega(k/\log k)$, it is possible to consistently estimate in total variation the \emph{profile} of the population, 
defined as the empirical distribution of the sizes of each type, which determines many symmetric properties of the population. We also prove
that in the linear regime of $m=c k$ for any constant $c$ the optimal rate is $\Theta(1/\log k)$. 
Our estimator is based on Wolfowitz's minimum distance method, which entails solving a linear program (LP) of size $k$.
We show that there is a single infinite-dimensional LP whose value simultaneously characterizes the risk of the minimum distance estimator and certifies its minimax optimality. The sharp convergence rate is obtained by evaluating this LP using complex-analytic techniques. 	
