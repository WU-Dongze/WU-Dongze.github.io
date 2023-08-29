---
title: "MetaLoc: Learning to Learn Wireless Localization"
collection: publications
accepted: yes
date: 2023-08-14
permalink: /publication/2023-07-01-paper-title-number-1
venue: 'IEEE Journal on Selected Areas in Communications'
citation: 'J. Gao, D. Wu., F. Yin, Q. Kong, L. Xu, and S. Cui, "MetaLoc: Learning to Learn Wireless Localization," in IEEE Journal on Selected Areas in Communication, 2023'
---

Latest IF=16.4; Ranked among the top 5 IEEE journals in all areas and recognized as the top journal for technical articles in communication engineering

To view my main contributions to the paper, please refer to <https://wu-dongze.github.io/portfolio/portfolio-1/>.

Present localization models mainly focus on specific environments, often neglecting their adaptation abilities in new testing scenarios. Our aim is to develop a localization framework with exceptional generalization capabilities, requiring minimal data and gradient steps for fine-tuning to be employed in unobserved test environments. Here are our key contributions:
* The paper introduces a pioneering localization framework called MetaLoc, which comprises of: (1) A centralized paradigm based on Model-Agnostic Meta-Learning (MAML) and (2) A distributed paradigm combining MAML with task similarity (MAML-TS) and MAML with Domain Generalization (MAML-DG)
* MetaLoc stands out from the crowd by quickly and efficiently adapting to new environments through a small number of newly collected measurements and only 10 gradient steps, which breaks through the traditional environment-specific localization bottleneck.
* Theoretical Contributions: We provide convergence analysis and first-order optimality analysis for the loss functions associated with MAML and MAML-DG. We also derive an empirical upper bound for the theoretical generalization error of MAML, laying the groundwork for the evolution of MAML-TS.
* MetaLoc demonstrates: 1) Superior Localization Performance 2) Rapid adaptation to new or unseen testing scenarios 3) Enhanced Model Flexibility. Such attributes underscore its immense potential for broader applications in signal processing, including smart homes and telemedicine surgeries.

[Download paper here](https://arxiv.org/abs/2211.04258)


