---
title: "Minimax Analysis of Estimation Problems in Coherent Imaging"
collection: publications
permalink: /publications/minimax_coherent
excerpt: ''
date: 2025-01-11
venue: 'Preprint'
topic: 'computational_imaging'
citation: 'with Hao Xing and Arian Maleki'

paperurl: "https://janasoham.github.io/files/minimax_coherent.pdf"

---

Abstract
========

Unlike conventional imaging modalities, such as magnetic resonance imaging, which are often well described by a linear regression framework, coherent imaging systems follow a significantly more complex model. In these systems, the task is to estimate the unknown image ${\boldsymbol x}_o \in \mathbb{R}^n$ from observations ${\boldsymbol y}_1, \ldots, {\boldsymbol y}_L \in \mathbb{R}^m$ of the form
$
{\boldsymbol y}_l = A_l X_o {\boldsymbol w}_l + {\boldsymbol z}_l, \quad l = 1, \ldots, L,
$
where $X_o = \mathrm{diag}({\boldsymbol x}_o)$ is an $n \times n$ diagonal matrix, 
${\boldsymbol w}_1, \ldots, {\boldsymbol w}_L \stackrel{\text{i.i.d.}}{\sim} \mathcal{N}(0,I_n)$ represent speckle noise, 
and ${\boldsymbol z}_1, \ldots, {\boldsymbol z}_L \stackrel{\text{i.i.d.}}{\sim} \mathcal{N}(0,\sigma_z^2 I_m)$ denote additive noise. 
The matrices $A_1, \ldots, A_L$ are known forward operators determined by the imaging system.  

The fundamental limits of conventional imaging systems have been extensively studied through sparse linear regression models. However, the limits of coherent imaging systems remain largely unexplored. Our goal is to close this gap by characterizing the \emph{minimax risk of estimating} ${\boldsymbol x}_o$ in high-dimensional settings.
 
Motivated by insights from sparse regression, we observe that the structure of ${\boldsymbol x}_o$ plays a crucial role in determining the estimation error. In this work, we adopt a general notion of structure based on the covering numbers, which is more appropriate for coherent imaging systems.  We show that the minimax mean squared error (MSE) scales as
$
\frac{\max(\sigma_z^4,\, m^2,\, n^2)\, k \log n}{m^2 n L},
$
where $k$ is a parameter that quantifies the effective complexity of the class of images.
 
