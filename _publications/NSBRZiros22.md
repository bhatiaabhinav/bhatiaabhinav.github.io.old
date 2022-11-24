---
title: "Selecting the Partial State Abstractions of MDPs: A Metareasoning Approach with Deep Reinforcement Learning"
authors: "Nashed, S.B., Svegliato, J., Bhatia, A., Russell S., Zilberstein, S."
collection: publications
permalink: publication/NSBRZiros22
# excerpt: 'TL;DR: Deep RL to adjust granularity of planning states'
date: 2022-10-23
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems'
venueshort: "IROS"
# paperurl: 'https://ojs.aaai.org/index.php/ICAPS/article/view/19842'
pdf: "../files/NSBRZiros22.pdf"
citation: 'Nashed, S.B., Svegliato, J., Bhatia, A., Russell S., Zilberstein, S. (2022). Selecting the partial state abstractions of MDPs: A metareasoning approach with deep reinforcement learning. In <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems</i>.'
tags:
  - metareasoning
  - real time planning
  - deep reinforcement learning
  - state abstractions
excerpt: ""
---



### Abstract
Markov decision processes (MDPs) are a common general-purpose model used in robotics for representing sequential decision-making problems. Given the complexity of robotics applications, a popular approach for approximately solving MDPs relies on state aggregation to reduce the size of the state space but at the expense of policy fidelity—offering a trade-off between policy quality and computation time. Naturally, this poses a challenging metareasoning problem: how can an autonomous system dynamically select different state abstractions that optimize this trade-off as it operates online? In this paper, we formalize this metareasoning problem with a notion of time-dependent utility and solve it using deep reinforcement learning. To do this, we develop several general, cheap heuristics that summarize the reward structure and transition topology of the MDP at hand to serve as effective features. Empirically, we demonstrate that our metareasoning approach outperforms several baseline approaches and a strong heuristic approach on a standard benchmark domain.


[PDF](../files/NSBRZiros22.pdf)

<!-- Should be a pdf link: -->

