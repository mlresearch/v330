---
title: 'CLoRA: Parameter-Efficient Continual Learning with Low-Rank Adaptation'
abstract: In the past, continual learning (CL) was mostly concerned with the problem
  of catastrophic forgetting in neural networks, that arises when incrementally learning
  a sequence of tasks. Current CL methods function within the confines of limited
  data access, without any restrictions imposed on computational resources. However,
  in real-world scenarios, the latter takes precedence as deployed systems are often
  computationally constrained. A major drawback of most CL methods is the need to
  retrain the entire model for each new task. The computational demands of retraining
  large models can be prohibitive, limiting the applicability of CL in environments
  with limited resources. Through CLoRA, we explore the applicability of Low-Rank
  Adaptation (LoRA), a parameter-efficient fine-tuning method for class-incremental
  semantic segmentation. CLoRA leverages a small set of parameters of the model and
  uses the same set for learning across all tasks. Results demonstrate the efficacy
  of CLoRA, achieving performance on par with and exceeding the baseline methods.
  We further evaluate CLoRA using NetScore, underscoring the need to factor in resource
  efficiency and evaluate CL methods beyond task performance. CLoRA significantly
  reduces the hardware requirements for training, making it well-suited for CL in
  resource-constrained environments after deployment.
year: '2025'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: muralidhara26a
month: 0
tex_title: 'CLoRA: Parameter-Efficient Continual Learning with Low-Rank Adaptation'
firstpage: 696
lastpage: 712
page: 696-712
order: 696
cycles: false
bibtex_author: Muralidhara, Shishir and Stricker, Didier and Schuster, Ren\'{e}
author:
- given: Shishir
  family: Muralidhara
- given: Didier
  family: Stricker
- given: René
  family: Schuster
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
pdf: https://raw.githubusercontent.com/mlresearch/v330/main/assets/muralidhara26a/muralidhara26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
