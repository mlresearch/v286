---
title: What is the Right Notion of Distance between Predict-then-Optimize Tasks?
abstract: Comparing datasets is a fundamental task in machine learning, essential
  for various learning paradigms-from evaluating train and test datasets for model
  generalization to using dataset similarity for detecting data drift. While traditional
  notions of dataset distances offer principled measures of similarity, their utility
  has largely been assessed through prediction error minimization. However, in Predict-then-Optimize
  (PtO) frameworks, where predictions serve as inputs for downstream optimization
  tasks, model performance is measured through decision regret rather than prediction
  error. In this work, we propose OTD$^3$ (Optimal Transport Decision-aware Dataset
  Distance), a novel dataset distance that incorporates downstream decisions in addition
  to features and labels. We show that traditional feature-label distances lack informativeness
  in PtO settings, while OTD$^3$ more effectively captures adaptation success. We
  also derive a PtO-specific adaptation bound based on this distance. Empirically,
  we show that our proposed distance accurately predicts model transferability across
  three different PtO tasks from the literature. Code is available at https://github.com/paularodr/OTD3
openreview: eoKZwI4ZCx
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rodriguez-diaz25a
month: 0
tex_title: What is the Right Notion of Distance between Predict-then-Optimize Tasks?
firstpage: 3570
lastpage: 3586
page: 3570-3586
order: 3570
cycles: false
bibtex_author: Rodriguez-Diaz, Paula and Kong, Lingkai and Wang, Kai and Alvarez-Melis,
  David and Tambe, Milind
author:
- given: Paula
  family: Rodriguez-Diaz
- given: Lingkai
  family: Kong
- given: Kai
  family: Wang
- given: David
  family: Alvarez-Melis
- given: Milind
  family: Tambe
date: 2025-07-11
address:
container-title: Proceedings of the Forty-first Conference on Uncertainty in Artificial
  Intelligence
volume: '286'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 7
  - 11
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/rodriguez-diaz25a/rodriguez-diaz25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
