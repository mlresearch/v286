---
title: Improved Variational Inference in Discrete VAEs using Error Correcting Codes
abstract: Despite advances in deep probabilistic models, learning discrete latent
  representations remains challenging. This work introduces a novel method to improve
  inference in discrete Variational Autoencoders by reframing the inference problem
  through a generative perspective. We conceptualize the model as a communication
  system, and propose to leverage Error-Correcting Codes (ECCs) to introduce redundancy
  in latent representations, allowing the variational posterior to produce more accurate
  estimates and reduce the variational gap. We present a proof-of-concept using a
  Discrete Variational Autoencoder with binary latent variables and low-complexity
  repetition codes, extending it to a hierarchical structure for disentangling global
  and local data features. Our approach significantly improves generation quality,
  data reconstruction, and uncertainty calibration, outperforming the uncoded models
  even when trained with tighter bounds such as the Importance Weighted Autoencoder
  objective. We also outline the properties that ECCs should possess to be effectively
  utilized for improved discrete variational inference.
software: https://github.com/mariamartinezgarcia/codedVAE
openreview: 66P2ioAYY4
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: martinez-garcia25a
month: 0
tex_title: Improved Variational Inference in Discrete VAEs using Error Correcting
  Codes
firstpage: 2973
lastpage: 3012
page: 2973-3012
order: 2973
cycles: false
bibtex_author: Mart\'{i}nez-Garc\'{i}a, Mar\'{i}a and Villacr\'{e}s, Grace and Mitchell,
  David and Olmos, Pablo M.
author:
- given: María
  family: Martínez-García
- given: Grace
  family: Villacrés
- given: David
  family: Mitchell
- given: Pablo M.
  family: Olmos
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/martinez-garcia25a/martinez-garcia25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
