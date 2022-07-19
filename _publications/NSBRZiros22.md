---
title: "Selecting the Partial State Abstractions of MDPs: A Metareasoning Approach with Deep Reinforcement Learning"
collection: publications
permalink: publication/NSBRZiros22
# excerpt: 'TL;DR: Deep RL to adjust granularity of planning states'
date: 2022-10-23
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
# paperurl: 'https://ojs.aaai.org/index.php/ICAPS/article/view/19842'
citation: 'Nashed, S.B., Svegliato, J., Bhatia, A., Zilberstein, S., Russell S. (2022). Selecting the partial state abstractions of MDPs: A metareasoning approach with deep reinforcement learning. In <i>Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems</i>.'
tags:
  - metareasoning
  - real time planning
  - deep reinforcement learning
  - state abstractions
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->

<!-- TL;DR: -->

### Abstract
Markov decision processes (MDPs) are a natural, general-purpose way to model stochastic decision-making problems. However, the complexity of solving MDPs forces the use of approximate solvers for many practical applications. One popular approximation method is abstraction through state aggregation, which reduces both the size of the problem and the fidelity of the solution. This also introduces a new problem: how to decide when to use different abstractions in order to optimize the trade-off between MDP policy quality and computation time. This paper formally introduces the choice of state abstraction as a metareasoning problem using time-dependent utility. We then provide several general, cheaply estimated features that serve as effective heuristics for determining abstractions. Finally, we show that one can further optimize performance by using deep reinforcement learning with these features.


[PDF](https://bhatiaabhinav.github.io/files/NSBRZiros22.pdf)

<!-- Should be a pdf link: -->

