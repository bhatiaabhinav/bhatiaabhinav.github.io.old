---
title: "Tuning the Hyperparameters of Anytime Planning: A Deep Reinforcement Learning Approach"
collection: publications
permalink: publication/BSZhsdip2021
excerpt: 'TL;DR: Deep RL to control hyperparameters of anytime algorithms at runtime to optimize quality of the final solution. Good results on _Anytime A*_ search algorithm.'
date: 2021-05-18
venue: 'ICAPS 2021 Workshop on Heuristics and Search for Domain-independent Planning'
paperurl: 'https://openreview.net/forum?id=c7hpFp_eRCo'  # Not necessarily a PDF. Can be an arxiv link or aaai link.
citation: 'Bhatia, A., Svegliato, J., & Zilberstein, S. (2021). Tuning the Hyperparameters of Anytime Planning: A Deep Reinforcement Learning Approach. In <i>ICAPS 2021 Workshop on Heuristics and Search for Domain-independent Planning.</i>'
tags:
  - metareasoning
  - hyperparameter tuning
  - anytime algorithms
  - real time planning
  - planning and reinforcement learning
  - anytime A*
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->

TL;DR: Deep RL to control hyperparameters of anytime algorithms at runtime to optimize quality of the final solution. Good results on _Anytime A*_ search algorithm.

### Abstract
Many anytime algorithms have adjustable hyperparameters that affect their speed and accuracy. However, while existing work on metareasoning has focused on deciding when to interrupt an anytime algorithm and act on the current solution, there has not been much work on tuning the hyperparameters of an anytime algorithm at runtime. This paper introduces a decision-theoretic metareasoning approach that can optimize both the hyperparameters and the stopping point of adjustable algorithms with deep reinforcement learning. First, we propose a generalization of an anytime algorithm called an adjustable algorithm that has hyperparameters that can be tuned at runtime. Next, we offer a meta-level control technique that monitors and controls an adjustable algorithm by using deep reinforcement learning. Finally, we demonstrate that an application of our approach to anytime weighted A* is effective on a range of common benchmark problems.

<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BSZhsdip2021.pdf)
[Talk](https://www.youtube.com/watch?v=6oiFsbbYOLM)

<iframe width="1034" height="582" src="https://www.youtube.com/embed/6oiFsbbYOLM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
\
A follow-up paper at ICAPS 2022: [Tuning the Hyperparameters of Anytime Planning: A Metareasoning Approach with Deep Reinforcement Learning](https://bhatiaabhinav.github.io/publication/BSNZicaps22)