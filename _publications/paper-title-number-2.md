---
title: "Bayesian-Boosted MetaLoc: Efficient Training and Guaranteed Generalization for Indoor Localization"
collection: publications
paperurl: 'https://arxiv.org/pdf/2308.14824v2.pdf'
---

**Submitted** to IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2024, the leading conference in signal processing.

Below are the main contributions of the paper:
* Provided a theoretical analysis using the PAC-learning and derived novel generalization bounds for Bayesian meta-learning, which were further optimized to develop a Bayes-optimal hyper-posterior with performance guarantees
* To further enhance computational efficiency, we improved the Stein-Variational Gradient-Descent (SVGD) for sampling the high-dimensional hyper-posteriors, aided with Monte Carlo methods and importance sampling
* Developed a novel framework featuring two main stages: the meta-training stage aimed at sampling posteriors from the optimal hyper-posterior using SVGD and past tasks from different distributions; and the online stage for rapid fine-tuning of these sampled optimal posteriors, using only a few data from a new distribution for subsequent testing
* On our complex localization datasets, our model, trained with only 100 tasks, demonstrated efficient training, reduced overfitting, and strong generalization, consistently outperforming state-of-the-art models trained with 10,000 tasks

[Download paper here](https://arxiv.org/pdf/2308.14824v2.pdf)

