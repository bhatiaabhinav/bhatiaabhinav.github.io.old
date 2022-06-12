---
title: "Tuning the Hyperparameters of Anytime Planning: A Metareasoning Approach with Deep Reinforcement Learning"
collection: publications
permalink: publication/BSNZicaps22
excerpt: 'TLDR: Deep RL to determine optimal stopping point _and_ hyperparameters of anytime algorithms at runtime to optimize _utility_ of the final solution. Good results on _Anytime A*_ search algorithm and _RRT*_ motion planning algorithm.'
date: 2022-06-21
venue: 'Proceedings of the International Conference on Automated Planning and Scheduling'
paperurl: 'https://abhinavbhatia.me/files/BSNZicaps22.pdf'  # Not necessarily a PDF. Can be an arxiv link or aaai link. TODO: Add official link
citation: 'Bhatia, A., Svegliato, J., Nashed, S, & Zilberstein, S. (2022, June). Tuning the hyperparameters of anytime planning: A metareasoning approach with deep reinforcement learning. In <i>Proceedings of the 32nd International Conference on Automated Planning and Scheduling</i>.' # TODO: Add page num
tags:
  - metareasoning
  - hyperparameter tuning
  - anytime algorithms
  - real time planning
  - planning and reinforcement learning
  - anytime A*
  - RRT*
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->

### Abstract
Anytime planning algorithms often have hyperparameters that can be tuned at runtime to optimize their performance.  While work on metareasoning has focused on when to interrupt an anytime planner and act on the current plan, the scope of metareasoning can be expanded to tuning the hyperparameters of the anytime planner at runtime. This paper introduces a general, decision-theoretic metareasoning approach that optimizes both the stopping point and hyperparameters of anytime planning. We begin by proposing a generalization of the standard meta-level control problem for anytime algorithms. We then offer a meta-level control technique that monitors and controls an anytime algorithm using deep reinforcement learning. Finally, we show that our approach boosts performance on a common benchmark domain that uses anytime weighted A* to solve a range of heuristic search problems and a mobile robot application that uses RRT* to solve motion planning problems.


<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BSNZicaps22.pdf)
[poster](https://bhatiaabhinav.github.io/files/BSNZicaps22_poster.pdf)
