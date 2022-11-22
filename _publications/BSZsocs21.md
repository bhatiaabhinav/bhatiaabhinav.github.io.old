---
title: "On the Benefits of Randomly Adjusting Anytime Weighted A*"
authors: "Bhatia, A., Svegliato, J., & Zilberstein, S."
collection: publications
permalink: publication/BSZsocs21
excerpt: 'TL;DR: _Randomized Weighted A*_ tunes the weight in _Anytime Weighted A*_ randomly at runtime and outperforms every static weighted baseline.'
date: 2021-07-21
venue: 'Proceedings of the International Symposium on Combinatorial Search (SoCS)'
venueshort: "SoCS"
paperurl: 'https://ojs.aaai.org/index.php/SOCS/article/view/18558'  # Not necessarily a PDF. Can be an arXiv link or AAAI link.
citation: 'Bhatia, A., Svegliato, J., & Zilberstein, S. (2021). On the Benefits of Randomly Adjusting Anytime Weighted A. In <i>Proceedings of the International Symposium on Combinatorial Search</i> (Vol. 12, No. 1, pp. 116-120).'
tags:
  - random hyperparameter tuning
  - heuristic search
  - anytime A*
  - real time search
---

<!-- Everything written here will come on the paper's own webpage. All the above data except the excerpt will also appear automatically. -->
TL;DR: _Randomized Weighted A*_ tunes the weight in _Anytime Weighted A*_ randomly at runtime and outperforms every static weighted baseline.

### Abstract
_Anytime Weighted A\*_---an anytime heuristic search algorithm that uses a weight to scale the heuristic value of each node in the open list---has proven to be an effective way to manage the trade-off between solution quality and computation time in heuristic search. Finding the best weight, however, is challenging because it depends on not only the characteristics of the domain and the details of the instance at hand, but also the available computation time. We propose a randomized version of this algorithm, called _Randomized Weighted A\*_, that randomly adjusts its weight at runtime and show a counterintuitive phenomenon: RWA* generally performs as well or better than AWA* with the best static weight on a range of benchmark problems. The result is a simple algorithm that is easy to implement and performs consistently well without any offline experimentation or parameter tuning.


<!-- Should be a pdf link: -->
[PDF](https://bhatiaabhinav.github.io/files/BSZsocs21.pdf)
[Poster](https://bhatiaabhinav.github.io/files/BSZsocs21_poster.pdf)
[Code](https://github.com/bhatiaabhinav/AnytimeWeightedAStar.jl)
[Talk](https://slideslive.com/38965417?slide=1)


<iframe src="https://slideslive.com/embed/presentation/38965417?slide=1" width="1034" height="582" allow="autoplay; fullscreen" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-top-navigation" frameborder="0" scrolling="no"></iframe>