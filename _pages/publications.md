---
title: "Publications"
excerpt: "About me"
permalink: /publications/
author_profile: true
---

## [Closing the Computational-Statistical Gap in Best Arm Identification for Combinatorial Semi-bandits](https://openreview.net/forum?id=8jg8z3ASiw)
* **[Ruo-Chun Tzeng](https://scholar.google.com/citations?user=jntcHQ0AAAAJ)**, [Po-An Wang](https://scholar.google.com/citations?user=kzXIxFYAAAAJ), [Alexandre Proutiere](https://scholar.google.com/citations?user=g5sya5cAAAAJ), [Chi-Jen Lu](https://scholar.google.com/citations?user=B_SGfJoAAAAJ)
* Advances in Neural Information Processing Systems (NeurIPS), 2023
* [paper](https://openreview.net/attachment?id=8jg8z3ASiw&name=supplementary_material), [code](https://github.com/rctzeng/NeurIPS2023-PerturbedFWS), [poster](https://rctzeng.github.io/posters/NeurIPS2023-PFWS.pdf), [5-min slides](https://rctzeng.github.io/slides/NeurIPS2023-PFWS_5min.pdf), [5-min talk](https://www.youtube.com/watch?v=ilGufKXJtII)
* Summary: 
The proposed algorithm (P-FWS) is the first polynomial-time algorithm that achieves minimal sample complexity in high confidence regime and has polynomial sample complexity in moderate confidence regime. Its designed is based on:\
 $\,\,$ (i) A structural property discovered in the Lagrangian dual function associated with the sample complexity lowerbound $T^{\star}(\mu)$;\
 $\,\,$ (ii) Such structural property allows us to design an efficient but non-standard two-player algorithm (MCP) to solve the inner optimization of $T^{\star}(\mu)$;\
 $\,\,$ (iii) The outer optimization of $T^{\star}(\mu)$ is solved by stochastic smoothed FW-based algorithm whose required gradients are estimated only by using the linear maximization.

## [Improved analysis of randomized SVD for top-eigenvector approximation](https://proceedings.mlr.press/v151/tzeng22a.html)
* **[Ruo-Chun Tzeng](https://scholar.google.com/citations?user=jntcHQ0AAAAJ)**, [Po-An Wang](https://scholar.google.com/citations?user=kzXIxFYAAAAJ), Florian Adriaens, [Aristides Gionis](https://scholar.google.se/citations?hl=en&user=11JgipcAAAAJ), and [Chi-Jen Lu](https://scholar.google.com/citations?user=B_SGfJoAAAAJ)
* *International Conference on Artificial Intelligence and Statistics (AISTATS)*, 2022
* [paper](https://rctzeng.github.io/papers/AISTATS2022-SSCG.pdf), [code](https://github.com/rctzeng/AISTATS22-Improved-analysis-of-RSVD-for-top-eigenvector-approx), [slides](https://rctzeng.github.io/slides/AISTATS2022-SSCG.pdf), [poster](https://rctzeng.github.io/posters/AISTATS2022-SSCG.pdf), [video](https://youtu.be/0_R05EyPl14)
* Summary: (i) sharpened analysis of Randomized SVD for top-1 eigenvector (especially under $o(\ln n)$ passes) for PSD matrices and for indefinite matrices (under some additional assumptions); (ii) found that mixing 0/1 Bernoulli with Gaussian distribution in random projection is useful for [conflicting group detection](https://proceedings.neurips.cc//paper/2020/hash/7cc538b1337957dae283c30ad46def38-Abstract.html)
* Typo: On Page 6 (the 2nd-last line), $S \sim Bernoulli(p)^{n\times d}$ should be $S \sim \mathcal{N}(0,1)^{n\times d}$
* Presented on [Conference on the Mathematics of Complex Data 2022](https://mathdatalab.org/) and [KTH ML Day 2023](https://www.digitalfutures.kth.se/event/machine-learning-day-2023-on-17-may/)

## [Fast Pure Exploration via Frank-Wolfe](https://openreview.net/forum?id=cD2Ls4qXTc)
* [Po-An Wang](https://scholar.google.com/citations?user=kzXIxFYAAAAJ), **[Ruo-Chun Tzeng](https://scholar.google.com/citations?user=jntcHQ0AAAAJ)**, and [Alexandre Proutiere](https://scholar.google.com/citations?user=g5sya5cAAAAJ)
* *Advances in Neural Information Processing Systems (NeurIPS)*, 2021
* [paper](https://openreview.net/forum?id=cD2Ls4qXTc), [code](https://github.com/rctzeng/NeurIPS2021-Fast-Pure-Exploration-via-Frank-Wolfe), [slides](https://rctzeng.github.io/slides/NeurIPS2021-FWS.pdf)
* Summary: (i) proposed a simple algorithm (Frank-Wolfe Sampling) achieving minimal sample complexity asymptotically ($\delta\to0$) for many pure exploration tasks under various structures; (ii) derived the first non-asymptotic sample complexity upper bound with explict dependence on task-specific parameters
* Presented by Po-An on [Conference on the Mathematics of Complex Data 2022](https://mathdatalab.org/)

## [Discovering conflicting groups in signed networks](https://proceedings.neurips.cc//paper/2020/hash/7cc538b1337957dae283c30ad46def38-Abstract.html)
* **[Ruo-Chun Tzeng](https://scholar.google.com/citations?user=jntcHQ0AAAAJ)**, [Bruno Ordozgoiti](https://scholar.google.se/citations?user=pUnVutMAAAAJ), and [Aristides Gionis](https://scholar.google.se/citations?hl=en&user=11JgipcAAAAJ)
* *Advances in Neural Information Processing Systems (NeurIPS)*, 2020
* [paper](https://proceedings.neurips.cc//paper/2020/hash/7cc538b1337957dae283c30ad46def38-Abstract.html), [code](https://github.com/rctzeng/SCG-NeurIPS2020), [slides](https://rctzeng.github.io/slides/NeurIPS2020-SCG.pdf), [poster](https://rctzeng.github.io/posters/NeurIPS2020-SCG.pdf), [2min talk](https://youtu.be/akyNJURM68g)
* Summary: (i) decomposed the task of $k$-conflicting group detection into subproblems of [QP-Ratio](https://dl.acm.org/doi/abs/10.1007/978-3-642-31594-7_10) variants (by spectral graph theory); (ii) designed a provable eigenvector-based algorithm for a QP-Ratio variant
* Presented on [KTH ML Day 2022](https://www.digitalfutures.kth.se/event/machine-learning-day/)

## [Distributed, egocentric representations of graphs for detecting critical structures](http://proceedings.mlr.press/v97/tzeng19a)
* **[Ruo-Chun Tzeng](https://scholar.google.com/citations?user=jntcHQ0AAAAJ)**, and [Shan-Hung Wu](https://scholar.google.com/citations?user=xjzRJwMAAAAJ)
* *International Conference on Machine Learning (ICML)*, 2019
* [paper](http://proceedings.mlr.press/v97/tzeng19a), [code](https://github.com/rctzeng/EgoCNN), [slides](https://rctzeng.github.io/slides/ICML2019-EgoCNN.pdf)
* Summary: (i) designed an interpretable model for graph supervised learning; (ii) empirically showed that weight-tying technique helps detect scale-free patterns