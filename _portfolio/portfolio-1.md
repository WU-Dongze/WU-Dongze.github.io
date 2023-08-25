---
title: "Major Contributions in MetaLoc: Learning to Learn Indoor Localization"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/MAMLDG_1.png'>"
collection: portfolio
---

My major contributions to MetaLoc span three areas: 1) Model Development, 2) Mathematical Derivations, and 3) Code and Dataset Maintenance.

The development of Model-Agnostic Meta-Learning with Domain Generalization (MAML-DG)
===
Addressing the challenges of vanilla MAML's slower convergence speed and suboptimal generalization capabilities (as introduced by Chelsea Fin in 2017), I enhanced the algorithm and proposed the MAML-DG. This was achieved by modifying the loss function to mimic real-time train-test domain shifts, ensuring the model's fast adaptability across diverse domains. The subsequent content shows the development and mathematical analysis of MAML-DG, proposed by me:
![avatar](/images/MAMLDG_1.png)
![avatar](/images/MAMLDG_2.png)

Mathematical Derivations
===
Drawing inspiration from the prior study, "Task Similarity Aware Meta Learning: Theory-Inspired Improvement on MAML," I further derived an empirical error bound for the theoretical generalization error of MAML. This theorem laid the foundation for the theoretical aspects of MetaLoc and inspired me to create the MAML-DG algorithm. The theorem is articulated as follows:
![avatar](/images/Theorem_1.png)

Code and Dataset Maintenance
===
