---
title: 'LaRa: Latents and Rays for Multi-Camera Bird’s-Eye-View Semantic Segmentation'
section: Poster
openreview: abd_D-iVjk0
abstract: Recent works in autonomous driving have widely adopted the bird’seye-view
  (BEV) semantic map as an intermediate representation of the world. Online prediction
  of these BEV maps involves non-trivial operations such as multi-camera data extraction
  as well as fusion and projection into a common topview grid. This is usually done
  with error-prone geometric operations (e.g., homography or back-projection from
  monocular depth estimation) or expensive direct dense mapping between image pixels
  and pixels in BEV (e.g., with MLP or attention). In this work, we present ‘LaRa’,
  an efficient encoder-decoder, transformer-based model for vehicle semantic segmentation
  from multiple cameras. Our approach uses a system of cross-attention to aggregate
  information over multiple sensors into a compact, yet rich, collection of latent
  representations. These latent representations, after being processed by a series
  of selfattention blocks, are then reprojected with a second cross-attention in the
  BEV space. We demonstrate that our model outperforms the best previous works using
  transformers on nuScenes. The code and trained models are available at https://github.com/valeoai/LaRa.
software: https://github.com/valeoai/LaRa
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bartoccioni23a
month: 0
tex_title: 'LaRa: Latents and Rays for Multi-Camera Bird’s-Eye-View Semantic Segmentation'
firstpage: 1663
lastpage: 1672
page: 1663-1672
order: 1663
cycles: false
bibtex_author: Bartoccioni, Florent and Zablocki, Eloi and Bursuc, Andrei and Perez,
  Patrick and Cord, Matthieu and Alahari, Karteek
author:
- given: Florent
  family: Bartoccioni
- given: Eloi
  family: Zablocki
- given: Andrei
  family: Bursuc
- given: Patrick
  family: Perez
- given: Matthieu
  family: Cord
- given: Karteek
  family: Alahari
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
pdf: https://proceedings.mlr.press/v205/bartoccioni23a/bartoccioni23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v205/bartoccioni23a/bartoccioni23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
