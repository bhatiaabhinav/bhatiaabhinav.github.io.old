---
title: "Resource Constrained Deep Reinforcement Learning"
authors: "Bhatia, A., Varakantham, P., & Kumar, A."
collection: publications
permalink: publication/BVKicaps2019
excerpt: 'TL;DR: Deep RL to optimize constrained resource allocation at city scale. Good results on realistic datasets.'
date: 2019-05-25
venue: 'Proceedings of the International Conference on Automated Planning and Scheduling'
paperurl: 'https://ojs.aaai.org/index.php/ICAPS/article/view/3528'  # Not necessarily a PDF. Can be an arxiv link or aaai link.
citation: 'Bhatia, A., Varakantham, P., & Kumar, A. (2019). Resource Constrained Deep Reinforcement Learning. In <i>Proceedings of the International Conference on Automated Planning and Scheduling, 29</i>(1), 610-620.'
tags:
  - contrained optimization
  - resource allocation
  - deep reinforcement learning
  - DDPG
  - city planning
  - emergency response systems
  - bike sharing
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->

TL;DR: Deep RL to optimize constrained resource allocation at city scale. Good results on realistic datasets.

### Abstract
In urban environments, resources have to be constantly matched to the “right” locations where customer demand is present. For instance, ambulances have to be matched to base stations regularly so as to reduce response time for emergency incidents in ERS (Emergency Response Systems); vehicles (cars, bikes among others) have to be matched to docking stations to reduce lost demand in shared mobility systems. Such problems are challenging owing to the demand uncertainty, combinatorial action spaces and constraints on allocation of resources (e.g., total resources, minimum and maximum number of resources at locations and regions).

Existing systems typically employ myopic and greedy optimization approaches to optimize resource allocation. Such approaches typically are unable to handle surges or variances in demand patterns well. Recent work has demonstrated the ability of Deep RL methods in adapting well to highly uncertain environments. However, existing Deep RL methods are unable to handle combinatorial action spaces and constraints on allocation of resources. To that end, we have developed three approaches on top of the well known actor-critic approach, DDPG (Deep Deterministic Policy Gradient) that are able to handle constraints on resource allocation. We also demonstrate that they are able to outperform leading approaches on simulators validated on semi-real and real data sets.

<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BVKicaps2019.pdf)
[Talk](https://www.youtube.com/embed/qGLRxfKD40s?start=2529&end=3816)

<iframe width="1034" height="582" src="https://www.youtube.com/embed/qGLRxfKD40s?start=2529&end=3816" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>