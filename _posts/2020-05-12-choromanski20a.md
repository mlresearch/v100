---
title: Provably Robust Blackbox Optimization for Reinforcement Learning
abstract: Interest in derivative-free optimization (DFO) and “evolutionary strategies”
  (ES) has recently surged in the Reinforcement Learning (RL) community, with growing
  evidence that they can match state of the art methods for policy optimization problems
  in Robotics. However, it is well known that DFO methods suffer from prohibitively
  high sampling complexity. They can also be very sensitive to noisy rewards and stochastic
  dynamics. In this paper, we propose a new class of algorithms, called Robust Blackbox
  Optimization (RBO). Remarkably, even if up to 23% of all the measurements are arbitrarily
  corrupted, RBO can provably recover gradients to high accuracy. RBO relies on learning
  gradient flows using robust regression methods to enable off-policy updates. On
  several MuJoCo robot control tasks, when all other RL approaches collapse in the
  presence of adversarial noise, RBO is able to train policies effectively. We also
  show that RBO can be applied to legged locomotion tasks including path tracking
  for quadruped robots.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: choromanski20a
month: 0
tex_title: Provably Robust Blackbox Optimization for Reinforcement Learning
firstpage: 683
lastpage: 696
page: 683-696
order: 683
cycles: false
bibtex_author: Choromanski, Krzysztof and Pacchiano, Aldo and Parker-Holder, Jack
  and Tang, Yunhao and Jain, Deepali and Yang, Yuxiang and Iscen, Atil and Hsu, Jasmine
  and Sindhwani, Vikas
author:
- given: Krzysztof
  family: Choromanski
- given: Aldo
  family: Pacchiano
- given: Jack
  family: Parker-Holder
- given: Yunhao
  family: Tang
- given: Deepali
  family: Jain
- given: Yuxiang
  family: Yang
- given: Atil
  family: Iscen
- given: Jasmine
  family: Hsu
- given: Vikas
  family: Sindhwani
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
pdf: http://proceedings.mlr.press/v100/choromanski20a/choromanski20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
