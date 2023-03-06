---
title: Bayesian Object Models for Robotic Interaction with Differentiable Probabilistic
  Programming
section: Poster
openreview: QSUsBMuw0uV
abstract: 'A hallmark of human intelligence is the ability to build rich mental models
  of previously unseen objects from very few interactions. To achieve true, continuous
  autonomy, robots too must possess this ability. Importantly, to integrate with the
  probabilistic robotics software stack, such models must encapsulate the uncertainty
  (resulting from noisy dynamics and observation models) in a prescriptive manner.
  We present Bayesian Object Models (BOMs): generative (probabilistic) models that
  encode both the structural and kinodynamic attributes of an object. BOMs are implemented
  in the form of a differentiable probabilistic program that models latent scene structure,
  object dynamics, and observation models. This allows for efficient and automated
  Bayesian inference – samples (object trajectories) drawn from the BOM are compared
  with a small set of real-world observations and used to compute a likelihood function.
  Our model comprises a differentiable tree structure sampler and a differentiable
  physics engine, enabling gradient computation through this likelihood function.
  This enables gradient-based Bayesian inference to efficiently update the distributional
  parameters of our model. BOMs outperform several recent approaches, including differentiable
  physics-based, gradient-free, and neural inference schemes. Further information
  at: https://bayesianobjects.github.io/'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jatavallabhula23a
month: 0
tex_title: Bayesian Object Models for Robotic Interaction with Differentiable Probabilistic
  Programming
firstpage: 1563
lastpage: 1574
page: 1563-1574
order: 1563
cycles: false
bibtex_author: Jatavallabhula, Krishna Murthy and Macklin, Miles and Fox, Dieter and
  Garg, Animesh and Ramos, Fabio
author:
- given: Krishna Murthy
  family: Jatavallabhula
- given: Miles
  family: Macklin
- given: Dieter
  family: Fox
- given: Animesh
  family: Garg
- given: Fabio
  family: Ramos
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
pdf: https://proceedings.mlr.press/v205/jatavallabhula23a/jatavallabhula23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v205/jatavallabhula23a/jatavallabhula23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
