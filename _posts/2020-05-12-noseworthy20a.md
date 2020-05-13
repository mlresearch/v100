---
title: Task-Conditioned Variational Autoencoders for Learning Movement Primitives
abstract: Consider a task such as pouring liquid from a cup into a container. Some
  parameters, such as the location of the pour, are crucial to task success, while
  others, such as the length of the pour, can exhibit larger variation. In this work,
  we propose a method that differentiates between specified task parameters and learned
  manner parameters. We would like to allow a designer to specify a subset of the
  parameters while learning the remaining parameters from a set of demonstrations.
  This is difficult because the learned parameters need to be interpretable and remain
  independent of the specified task parameters. To disentangle the parameter sets,
  we propose a Task-Conditioned Variational Autoencoder (TC-VAE) that conditions on
  the specified task parameters while learning the rest from demonstrations. We use
  an adversarial loss function to ensure the learned parameters encode no information
  about the task parameters. We evaluate our method on pouring demonstrations on a
  Baxter robot from the MIME dataset. We show that the TC-VAE can generalize to task
  instances unseen during training and that changing the learned parameters does not
  affect the success of the motion.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: noseworthy20a
month: 0
tex_title: Task-Conditioned Variational Autoencoders for Learning Movement Primitives
firstpage: 933
lastpage: 944
page: 933-944
order: 933
cycles: false
bibtex_author: Noseworthy, Michael and Paul, Rohan and Roy, Subhro and Park, Daehyung
  and Roy, Nicholas
author:
- given: Michael
  family: Noseworthy
- given: Rohan
  family: Paul
- given: Subhro
  family: Roy
- given: Daehyung
  family: Park
- given: Nicholas
  family: Roy
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
pdf: http://proceedings.mlr.press/v100/noseworthy20a/noseworthy20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
