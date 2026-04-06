---
title: Reinitializing weights vs units for maintaining plasticity in neural networks
abstract: 'Loss of plasticity is a phenomenon in which a neural network loses its
  ability to learn when trained for an extended time on non-stationary data. It is
  a crucial problem to overcome when designing systems that learn continually. An
  effective technique for preventing loss of plasticity is reinitializing parts of
  the network. In this paper, we compare two different reinitialization schemes: reinitializing
  units vs reinitializing weights. We propose a new algorithm, which we name \textit{selective
  weight reinitialization}, for reinitializing the least useful weights in a network.  We
  compare our algorithm to continual backpropagation and ReDo, two previously proposed
  algorithms that reinitialize units in the network. Through our experiments in continual
  supervised learning problems, we identify two settings when reinitializing weights
  is more effective at maintaining plasticity than reinitializing units: (1) when
  the network has a small number of units and (2) when the network includes layer
  normalization. Conversely, reinitializing weights and units are equally effective
  at maintaining plasticity when the network is of sufficient size and does not include
  layer normalization.  We found that reinitializing weights maintains plasticity
  in a wider variety of settings than reinitializing units.'
year: '2025'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hernandez-garcia26a
month: 0
tex_title: Reinitializing weights vs units for maintaining plasticity in neural networks
firstpage: 776
lastpage: 806
page: 776-806
order: 776
cycles: false
bibtex_author: Hernandez-Garcia, J. Fernando and Dohare, Shibhansh and Luo, Jun and
  Sutton, Richard S.
author:
- given: J. Fernando
  family: Hernandez-Garcia
- given: Shibhansh
  family: Dohare
- given: Jun
  family: Luo
- given: Richard S.
  family: Sutton
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
pdf: https://raw.githubusercontent.com/mlresearch/v330/main/assets/hernandez-garcia26a/hernandez-garcia26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
