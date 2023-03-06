---
title: Learning Temporally Extended Skills in Continuous Domains as Symbolic Actions
  for Planning
section: Oral
openreview: t-IO7wCaNgH
abstract: Problems which require both long-horizon planning and continuous control
  capabilities pose significant challenges to existing reinforcement learning agents.
  In this paper we introduce a novel hierarchical reinforcement learning agent which
  links temporally extended skills for continuous control with a forward model in
  a symbolic discrete abstraction of the environment’s state for planning. We term
  our agent SEADS for Symbolic Effect-Aware Diverse Skills. We formulate an objective
  and corresponding algorithm which leads to unsupervised learning of a diverse set
  of skills through intrinsic motivation given a known state abstraction. The skills
  are jointly learned with the symbolic forward model which captures the effect of
  skill execution in the state abstraction. After training, we can leverage the skills
  as symbolic actions using the forward model for long-horizon planning and subsequently
  execute the plan using the learned continuous-action control skills. The proposed
  algorithm learns skills and forward models that can be used to solve complex tasks
  which require both continuous control and long-horizon planning capabilities with
  high success rate. It compares favorably with other flat and hierarchical reinforcement
  learning baseline agents and is successfully demonstrated with a real robot.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: achterhold23a
month: 0
tex_title: Learning Temporally Extended Skills in Continuous Domains as Symbolic Actions
  for Planning
firstpage: 225
lastpage: 236
page: 225-236
order: 225
cycles: false
bibtex_author: Achterhold, Jan and Krimmel, Markus and Stueckler, Joerg
author:
- given: Jan
  family: Achterhold
- given: Markus
  family: Krimmel
- given: Joerg
  family: Stueckler
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
pdf: https://proceedings.mlr.press/v205/achterhold23a/achterhold23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v205/achterhold23a/achterhold23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
