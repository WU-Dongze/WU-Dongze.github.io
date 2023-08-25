---
title: "Major Contributions in MetaLoc: Learning to Learn Indoor Localization"
excerpt: "<br/><img src='/images/overview.png'>"
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
I authored the code for MAML-DG and contributed to the coding of MAML-TS. All MetaLoc codes are now public and maintained by me. Additionally, to enable objective performance evaluation of various localization methods, we introduced a public dataset, which is also maintained by me. Please access both the codes and dataset via my GitHub: <https://github.com/dongzewuu/MetaLoc>
