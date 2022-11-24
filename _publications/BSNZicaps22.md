---
title: "Tuning the Hyperparameters of Anytime Planning: A Metareasoning Approach with Deep Reinforcement Learning"
authors: "Bhatia, A., Svegliato, J., Nashed, S. B., & Zilberstein, S."
collection: publications
permalink: publication/BSNZicaps22
tldr: 'Deep RL to determine optimal stopping point _and_ hyperparameters of anytime algorithms at runtime to optimize _utility_ of the final solution. Good results on _Anytime A*_ search algorithm and _RRT*_ motion planning algorithm.'
date: 2022-06-13
venue: 'Proceedings of the International Conference on Automated Planning and Scheduling'
venueshort: "ICAPS"
pdf: "https://bhatiaabhinav.github.io/files/BSNZicaps22.pdf"
paperurl: 'https://ojs.aaai.org/index.php/ICAPS/article/view/19842'
citation: 'Bhatia, A., Svegliato, J., Nashed, S. B., & Zilberstein, S. (2022). Tuning the Hyperparameters of Anytime Planning: A Metareasoning Approach with Deep Reinforcement Learning. In <i>Proceedings of the International Conference on Automated Planning and Scheduling, 32</i>(1), 556-564.'
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

TL;DR: Deep RL to determine optimal stopping point _and_ hyperparameters of anytime algorithms at runtime to optimize _utility_ of the final solution. Good results on _Anytime A*_ search algorithm and _RRT*_ motion planning algorithm.

### Abstract
Anytime planning algorithms often have hyperparameters that can be tuned at runtime to optimize their performance.  While work on metareasoning has focused on when to interrupt an anytime planner and act on the current plan, the scope of metareasoning can be expanded to tuning the hyperparameters of the anytime planner at runtime. This paper introduces a general, decision-theoretic metareasoning approach that optimizes both the stopping point and hyperparameters of anytime planning. We begin by proposing a generalization of the standard meta-level control problem for anytime algorithms. We then offer a meta-level control technique that monitors and controls an anytime algorithm using deep reinforcement learning. Finally, we show that our approach boosts performance on a common benchmark domain that uses anytime weighted A* to solve a range of heuristic search problems and a mobile robot application that uses RRT* to solve motion planning problems.


<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BSNZicaps22.pdf)
[Poster](https://bhatiaabhinav.github.io/files/BSNZicaps22_poster.pdf)
[Code](https://github.com/bhatiaabhinav/Metareasoning.jl)
[Talk](https://www.youtube.com/watch?v=sQE5AUTDJ38)

<iframe width="1110" height="624" src="https://www.youtube.com/embed/sQE5AUTDJ38" title="Tuning Hyperparameters of Anytime Planning: A Metareasoning Approach with Deep RL - ICAPS 2022" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>