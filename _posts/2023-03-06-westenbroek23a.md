---
title: Lyapunov Design for Robust and Efficient Robotic Reinforcement Learning
section: Poster
openreview: Ef7xodOrgNW
abstract: Recent advances in the reinforcement learning (RL) literature have enabled
  roboticists to automatically train complex policies in simulated environments. However,
  due to the poor sample complexity of these methods, solving RL problems using real-world
  data remains a challenging problem. This paper introduces a novel cost-shaping method
  which aims to reduce the number of samples needed to learn a stabilizing controller.
  The method adds a term involving a Control Lyapunov Function (CLF) – an ‘energy-like’
  function from the model-based control literature – to typical cost formulations.
  Theoretical results demonstrate the new costs lead to stabilizing controllers when
  smaller discount factors are used, which is well-known to reduce sample complexity.
  Moreover, the addition of the CLF term ‘robustifies’ the search for a stabilizing
  controller by ensuring that even highly sub-optimal polices will stabilize the system.
  We demonstrate our approach with two hardware examples where we learn stabilizing
  controllers for a cartpole and an A1 quadruped with only seconds and a few minutes
  of fine-tuning data, respectively. Furthermore, simulation benchmark studies show
  that obtaining stabilizing policies by optimizing our proposed costs requires orders
  of magnitude less data compared to standard cost designs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: westenbroek23a
month: 0
tex_title: Lyapunov Design for Robust and Efficient Robotic Reinforcement Learning
firstpage: 2125
lastpage: 2135
page: 2125-2135
order: 2125
cycles: false
bibtex_author: Westenbroek, Tyler and Castaneda, Fernando and Agrawal, Ayush and Sastry,
  Shankar and Sreenath, Koushil
author:
- given: Tyler
  family: Westenbroek
- given: Fernando
  family: Castaneda
- given: Ayush
  family: Agrawal
- given: Shankar
  family: Sastry
- given: Koushil
  family: Sreenath
date: 2023-03-06
address:
container-title: Proceedings of The 6th Conference on Robot Learning
volume: '205'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 3
  - 6
pdf: https://proceedings.mlr.press/v205/westenbroek23a/westenbroek23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v205/westenbroek23a/westenbroek23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
