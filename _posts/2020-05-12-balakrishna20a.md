---
title: On-Policy Robot Imitation Learning from a Converging Supervisor
abstract: Existing on-policy imitation learning algorithms, such as DAgger, assume
  access to a fixed supervisor. However, there are many settings where the supervisor
  may evolve during policy learning, such as a human performing a novel task or an
  improving algorithmic controller. We formalize imitation learning from a “converging
  supervisor” and provide sublinear static and dynamic regret guarantees against the
  best policy in hindsight with labels from the converged supervisor, even when labels
  during learning are only from intermediate supervisors. We then show that this framework
  is closely connected to a class of reinforcement learning (RL) algorithms known
  as dual policy iteration (DPI), which alternate between training a reactive learner
  with imitation learning and a model-based supervisor with data from the learner.
  Experiments suggest that when this framework is applied with the state-of-the-art
  deep model-based RL algorithm PETS as an improving supervisor, it outperforms deep
  RL baselines on continuous control tasks and provides up to an 80-fold speedup in
  policy evaluation.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: balakrishna20a
month: 0
tex_title: On-Policy Robot Imitation Learning from a Converging Supervisor
firstpage: 24
lastpage: 41
page: 24-41
order: 24
cycles: false
bibtex_author: Balakrishna, Ashwin and Thananjeyan, Brijen and Lee, Jonathan and Li,
  Felix and Zahed, Arsh and Gonzalez, Joseph E. and Goldberg, Ken
author:
- given: Ashwin
  family: Balakrishna
- given: Brijen
  family: Thananjeyan
- given: Jonathan
  family: Lee
- given: Felix
  family: Li
- given: Arsh
  family: Zahed
- given: Joseph E.
  family: Gonzalez
- given: Ken
  family: Goldberg
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
pdf: http://proceedings.mlr.press/v100/balakrishna20a/balakrishna20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
