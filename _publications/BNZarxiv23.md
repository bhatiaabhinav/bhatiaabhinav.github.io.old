---
title: "RL$^3$: Boosting Meta Reinforcement Learning via RL inside RL$^2$"
authors: "Bhatia, A., Nashed, SB., & Zilberstein, S."
collection: publications
permalink: publication/BNZarxiv23
tldr: 'Incorporating task-specific Q-value estimates as inputs to a meta-RL policy can lead to improved generalization and better performance on long horizon tasks.'
date: 2023-06-28
venue: 'arXiv preprint arXiv:2306.15909'
venueshort: "ArXiv"
paperurl: 'https://arxiv.org/abs/2306.15909'
pdf: "../files/BNZarxiv23.pdf"
citation: 'Bhatia, A., Nashed, SB., & Zilberstein, S. (2023). RL$^3$: Boosting Meta Reinforcement Learning via RL inside RL$^2$. In <i>arXiv preprint arXiv:2306.15909</i>.'
tags:
  - meta reinforcement learning
  - deep reinforcement learning
excerpt: ""
---


### Abstract
Meta reinforcement learning (meta-RL) methods such as RL$^2$ have emerged as promising approaches for learning data-efficient RL algorithms tailored to a given task distribution. However, these RL algorithms struggle with long-horizon tasks and out-of-distribution tasks since they rely on recurrent neural networks to process the sequence of experiences instead of summarizing them into general RL components such as value functions. Moreover, even transformers have a practical limit to the length of histories they can efficiently reason about before training and inference costs become prohibitive. In contrast, traditional RL algorithms are data-inefficient since they do not leverage domain knowledge, but they do converge to an optimal policy as more data becomes available. In this paper, we propose RL$^3$, a principled hybrid approach that combines traditional RL and meta-RL by incorporating task-specific action-values learned through traditional RL as an input to the meta-RL neural network. We show that RL$^3$ earns greater cumulative reward on long-horizon and out-of-distribution tasks compared to RL$^2$, while maintaining the efficiency of the latter in the short term. Experiments are conducted on both custom and benchmark discrete domains from the meta-RL literature that exhibit a range of short-term, long-term, and complex dependencies.

[PDF](../files/BNZarxiv23.pdf)
[Code](https://github.com/bhatiaabhinav/RL3.jl)


#### RL$^3$ vs RL$^2$ Demo

<iframe width="1109" height="624" src="https://www.youtube.com/embed/sTQ9vFC53-k" title="RL² vs RL³ Demo | RL³: Boosting Meta-RL via RL inside RL²" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>