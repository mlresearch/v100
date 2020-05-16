---
title: A Divergence Minimization Perspective on Imitation Learning Methods
abstract: In many settings, it is desirable to learn decision-making and control policies
  through learning or bootstrapping from expert demonstrations. The most common approaches
  under this Imitation Learning (IL) framework are Behavioural Cloning (BC), and Inverse
  Reinforcement Learning (IRL). Recent methods for IRL have demonstrated the capacity
  to learn effective policies with access to a very limited set of demonstrations,
  a scenario in which BC methods often fail. Unfortunately, due to multiple factors
  of variation, directly comparing these methods does not provide adequate intuition
  for understanding this difference in performance. In this work, we present a unified
  probabilistic perspective on IL algorithms based on divergence minimization. We
  present f-MAX, an f-divergence generalization of AIRL [1], a state-of-the-art IRL
  method. f-MAX enables us to relate prior IRL methods such as GAIL [2] and AIRL [1],
  and understand their algorithmic properties. Through the lens of divergence minimization
  we tease apart the differences between BC and successful IRL approaches,and empirically
  evaluate these nuances on simulated high-dimensional continuous control domains.
  Our findings conclusively identify that IRL’s state-marginal matching objective
  contributes most to its superior performance. Lastly, we apply our new understanding
  of IL method to the problem of state-marginal matching, where we demonstrate that
  in simulated arm pushing environments we can teach agents a diverse range of behaviours
  using simply hand-specified state distributions and no reward functions or expert
  demonstrations. For datasets and reproducing results please refer to https://github.com/KamyarGh/rl_swiss/blob/master/reproducing/fmax_paper.md.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ghasemipour20a
month: 0
tex_title: A Divergence Minimization Perspective on Imitation Learning Methods
firstpage: 1259
lastpage: 1277
page: 1259-1277
order: 1259
cycles: false
bibtex_author: Ghasemipour, Seyed Kamyar Seyed and Zemel, Richard and Gu, Shixiang
author:
- given: Seyed Kamyar Seyed
  family: Ghasemipour
- given: Richard
  family: Zemel
- given: Shixiang
  family: Gu
date: 2020-05-12
address: 
publisher: PMLR
container-title: Proceedings of the Conference on Robot Learning
volume: '100'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 5
  - 12
pdf: http://proceedings.mlr.press/v100/ghasemipour20a/ghasemipour20a.pdf
extras:
- label: Source code
  link: https://github.com/KamyarGh/rl_swiss/blob/master/reproducing/fmax_paper.md
- label: Website
  link: https://sites.google.com/view/corl2019fmaxvideos/home
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
