---
title: Quasi-likelihood-based EM algorithm for regime-switching SDE
authors:
- admin
- Hiroki Masuda
date: '2024-12-01'
publishDate: '2025-07-10T02:52:12.136885Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2412.06305
abstract: This paper considers estimating the parameters in a regime-switching stochastic
  differential equation(SDE) driven by Normal Inverse Gaussian(NIG) noise. The model
  under consideration incorporates a continuous-time finite state Markov chain to
  capture regime changes, enabling a more realistic representation of evolving market
  conditions or environmental factors. Although the continuous dynamics are typically
  observable, the hidden nature of the Markov chain introduces significant complexity,
  rendering standard likelihood-based methods less effective. To address these challenges,
  we propose an estimation algorithm designed for discrete, high-frequency observations,
  even when the Markov chain is not directly observed. Our approach integrates the
  Expectation-Maximization (EM) algorithm, which iteratively refines parameter estimates
  in the presence of latent variables, with a quasi-likelihood method adapted to NIG
  noise. Notably, this method can simultaneously estimate parameters within both the
  SDE coefficients and the driving noise. Simulation results are provided to evaluate
  the performance of the algorithm. These experiments demonstrate that the proposed
  method provides reasonable estimation under challenging conditions.
tags:
- Statistics - Computation
links:
- name: URL
  url: http://arxiv.org/abs/2412.06305
share: false
---
