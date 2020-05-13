---
title: 'MAME : Model-Agnostic Meta-Exploration'
abstract: Meta-Reinforcement learning approaches aim to develop learning procedures
  that can adapt quickly to a distribution of tasks with the help of a few examples.
  Developing efficient exploration strategies capable of finding the most useful samples
  becomes critical in such settings. Existing approaches towards finding efficient
  exploration strategies add auxiliary objectives to promote exploration by the pre-update
  policy, however, this makes the adaptation using a few gradient steps difficult
  as the pre-update (exploration) and post-update (exploitation) policies are often
  quite different. Instead, we propose to explicitly model a separate exploration
  policy for the task distribution. Having two different policies gives more flexibility
  in training the exploration policy and also makes adaptation to any specific task
  easier. We show that using self-supervised or supervised learning objectives for
  adaptation allows for more efficient inner-loop updates and also demonstrate the
  superior performance of our model compared to prior works in this domain.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: gurumurthy20a
month: 0
tex_title: 'MAME : Model-Agnostic Meta-Exploration'
firstpage: 910
lastpage: 922
page: 910-922
order: 910
cycles: false
bibtex_author: Gurumurthy, Swaminathan and Kumar, Sumit and Sycara, Katia
author:
- given: Swaminathan
  family: Gurumurthy
- given: Sumit
  family: Kumar
- given: Katia
  family: Sycara
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
pdf: http://proceedings.mlr.press/v100/gurumurthy20a/gurumurthy20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
