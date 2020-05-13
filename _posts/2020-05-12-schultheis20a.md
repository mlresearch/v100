---
title: Receding Horizon Curiosity
abstract: Sample-efficient exploration is crucial not only for discovering rewarding
  experiences but also for adapting to environment changes in a task-agnostic fashion.
  A principled treatment of the problem of optimal input synthesis for system identification
  is provided within the framework of sequential Bayesian experimental design. In
  this paper, we present an effective trajectory-optimization-based approximate solution
  of this otherwise intractable problem that models optimal exploration in an unknown
  Markov decision process (MDP). By interleaving episodic exploration with Bayesian
  nonlinear system identification, our algorithm takes advantage of the inductive
  bias to explore in a directed manner, without assuming prior knowledge of the MDP.
  Empirical evaluations indicate a clear advantage of the proposed algorithm in terms
  of the rate of convergence and the final model fidelity when compared to intrinsic-motivation-based
  algorithms employing exploration bonuses such as prediction error and information
  gain. Moreover, our method maintains a computational advantage over a recent model-based
  active exploration (MAX) algorithm, by focusing on the information gain along trajectories
  instead of seeking a global exploration policy. A reference implementation of our
  algorithm and the conducted experiments is publicly available1.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: schultheis20a
month: 0
tex_title: Receding Horizon Curiosity
firstpage: 1278
lastpage: 1288
page: 1278-1288
order: 1278
cycles: false
bibtex_author: Schultheis, Matthias and Belousov, Boris and Abdulsamad, Hany and Peters,
  Jan
author:
- given: Matthias
  family: Schultheis
- given: Boris
  family: Belousov
- given: Hany
  family: Abdulsamad
- given: Jan
  family: Peters
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
pdf: http://proceedings.mlr.press/v100/schultheis20a/schultheis20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
