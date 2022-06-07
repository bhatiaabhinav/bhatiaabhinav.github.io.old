---
title: "Adaptive Rollout Length for Model-Based RL using Model-Free Deep RL"
collection: publications
permalink: publication/BTZarxiv22
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-06-06
venue: 'arXiv preprint arXiv:2206.02380'
paperurl: 'https://arxiv.org/abs/2206.02380'  # Not necessarily a PDF. Can be an arxiv link or aaai link. TODO: Add official link
citation: 'Bhatia, A., Thomas, PS., & Zilberstein, S. (2022, June). Adaptive Rollout Length for Model-Based RL using Model-Free Deep RL. In <i>arXiv preprint arXiv:2206.02380</i>.'
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->

### Abstract
Model-based reinforcement learning promises to learn an optimal policy from fewer interactions with the environment compared to model-free reinforcement learning by learning an intermediate model of the environment in order to predict future interactions. When predicting a sequence of interactions, the _rollout length_, which limits the prediction horizon, is a critical hyperparameter as accuracy of the predictions diminishes in the regions that are further away from real experience.

As a result, with a longer rollout length, an overall worse policy is learned in the long run. Thus, the hyperparameter provides a trade-off between quality and efficiency. In this work, we frame the problem of tuning the rollout length as a meta-level sequential decision-making problem that optimizes the final policy learned by model-based reinforcement learning given a fixed budget of environment interactions by adapting the hyperparameter dynamically based on feedback from the learning process, such as accuracy of the model and the remaining budget of interactions. We use model-free deep reinforcement learning to solve the meta-level decision problem and demonstrate that our approach outperforms common heuristic baselines on two well-known reinforcement learning environments.

<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BTZarxiv22.pdf)