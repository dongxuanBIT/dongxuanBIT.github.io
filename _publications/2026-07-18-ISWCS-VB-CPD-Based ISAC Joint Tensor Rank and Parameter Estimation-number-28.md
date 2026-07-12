---
title: "[C28] VB-CPD-Based ISAC: Joint Tensor Rank and Parameter Estimation"
collection: publications
category: conferences
permalink: /publication/2026-07-18-ISWCS-VB-CPD-Based ISAC Joint Tensor Rank and Parameter Estimation-number-28
excerpt: 'This paper investigates a unified multi-dimensional tensor modeling and parameter estimation framework.'
date: 2026-07-16
venue: '2026 20th International Symposium on Wireless Communication Systems (ISWCS)'
paperurl: 'http://dongxuanBIT.github.io/files/C28.pdf'
citation: 'Y. Zhang, T. Chan, and D. He, &quot;VB-CPD-Based ISAC: Joint Tensor Rank and Parameter Estimation,&quot; in <i>Proc. 2026 20th International Symposium on Wireless Communication Systems (ISWCS)</i>, Gold Coast, Australia, 2026, pp. 1-1.'
---

Integrated sensing and communication (ISAC) systems can realize both communication and sensing functionalities. However, it is challenging to sense multiple targets simultaneously due to the coupling between parameters, which require more efficient tools such as tensor-based parameter estimation to obtain the information of targets. Moreover, traditional tensor-based parameter estimation methods typically rely on fixed rank prerequisites, where the uncertainty in tensor rank inevitably leads to severe performance degradation due to overfitting or underfitting. To solve this problem, a unified multi-dimensional tensor modeling and parameter estimation framework is proposed in this paper. More specifically, we first develop a Variational Bayesian Canonical Polyadic Decomposition (VB-CPD) algorithm. By incorporating hierarchical sparsity-inducing priors, the proposed VB-CPD algorithm can autonomously determine the effective tensor rank and prune redundant components directly from highly coupled observations, thus eliminating the need for prior knowledge of the numbers of users or targets. Furthermore, an alternating parameter decoupling (APD) algorithm is proposed to sequentially resolve the highly nonlinear coupling among spatial angles, time delays, and Doppler shifts, thereby enabling accurate physical parameter extraction. Simulation results demonstrate that the proposed framework outperforms conventional tensor decomposition baselines in both rank identification and parameter estimation accuracy.
