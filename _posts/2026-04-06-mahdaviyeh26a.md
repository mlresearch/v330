---
title: Replay can provably increase forgetting
abstract: Continual learning seeks to enable machine learning systems to solve an
  increasing corpus of tasks sequentially. A critical challenge for continual learning
  is forgetting, where the performance on previously learned tasks decreases as new
  tasks are introduced. One of the commonly used techniques to mitigate forgetting,
  sample replay, has been shown empirically to reduce forgetting by retaining some
  examples from old tasks and including them in new training episodes. In this work,
  we provide a theoretical analysis of sample replay in an over-parameterized continual
  linear regression setting, where each task is given by a linear subspace and with
  enough replay samples, one would be able to eliminate forgetting. Our analysis focuses
  on sample replay and highlights the role of the replayed samples and the relationship
  between task subspaces. Surprisingly, we find that, even in a noiseless setting,
  forgetting can be non-monotonic with respect to the number of replay samples. We
  present tasks where replay can be *harmful* with respect to worst-case settings,
  and also in distributional settings where replay of randomly selected samples increases
  forgetting in expectation. We also give empirical evidence that harmful replay is
  not limited to training with linear models by showing similar behavior for a neural
  networks equipped with SGD.  Through experiments on a commonly used benchmark, we
  provide additional evidence that, even in seemingly benign scenarios, performance
  of the replay heavily depends on the choice of replay samples and the relationship
  between tasks.
year: '2025'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mahdaviyeh26a
month: 0
tex_title: Replay can provably increase forgetting
firstpage: 15
lastpage: 42
page: 15-42
order: 15
cycles: false
bibtex_author: Mahdaviyeh, Yasaman and Lucas, James and Ren, Mengye and Tolias, Andreas
  S. and Zemel, Richard and Pitassi, Toniann
author:
- given: Yasaman
  family: Mahdaviyeh
- given: James
  family: Lucas
- given: Mengye
  family: Ren
- given: Andreas S.
  family: Tolias
- given: Richard
  family: Zemel
- given: Toniann
  family: Pitassi
date: 2026-04-06
address:
container-title: Proceedings of The 4th Conference on Lifelong Learning Agents
volume: '330'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 4
  - 6
pdf: https://raw.githubusercontent.com/mlresearch/v330/main/assets/mahdaviyeh26a/mahdaviyeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
