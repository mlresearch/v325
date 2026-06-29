---
title: Zigzag Persistence of Large Language Models Representations
abstract: 'We analyze internal representations of large language models with zigzag
  persistent homology, treating depth as a discrete time axis for point clouds of
  last-token embeddings. At each layer we build a k-nearest-neighbors clique complex,
  connect adjacent layers via intersections, and summarize the resulting diagrams
  with effective persistence images. From these we derive two descriptors: Births’
  Relative Frequency (at what rate new p-dimensional features appear) and Inter-Layer
  Persistence (how long they survive across depth). On the SST movie reviews dataset
  and three open-source models (Llama-3.1, OSS-20B, Phi-4), we consistently observe
  three evolving phases: early rapid changes, a middle regime of stable organization,
  and a final reorganization before output. Using the stability signal (inter-layer
  persistence) to guide where to remove contiguous blocks of layers, we find that
  pruning within high-persistence regions maintains 5-shot MMLU performance (with
  the same trend visible even for the more pruning-sensitive OSS-20B). This suggests
  that zigzag-based summaries capture meaningful, system-level dynamics and can inform
  lightweight pruning.'
section: Extended Abstracts
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gardinazzi26a
month: 0
tex_title: Zigzag Persistence of Large Language Models Representations
firstpage: 120
lastpage: 129
page: 120-129
order: 120
cycles: false
bibtex_author: Gardinazzi, Yuri and Viswanathan, Karthik and Panerai, Giada and Ansuini,
  Alessio and Cazzaniga, Alberto and Biagetti, Matteo
author:
- given: Yuri
  family: Gardinazzi
- given: Karthik
  family: Viswanathan
- given: Giada
  family: Panerai
- given: Alessio
  family: Ansuini
- given: Alberto
  family: Cazzaniga
- given: Matteo
  family: Biagetti
date: 2026-06-29
address:
container-title: Proceedings of the Geometry, Topology, and Machine Learning Workshop
volume: '325'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 6
  - 29
pdf: https://raw.githubusercontent.com/mlresearch/v325/main/assets/gardinazzi26a/gardinazzi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
