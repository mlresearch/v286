---
title: 'Probabilistic Embeddings for Frozen Vision-Language Models: Uncertainty Quantification
  with Gaussian Process Latent Variable Models'
abstract: Vision-Language Models (VLMs) learn joint representations by mapping images
  and text into a shared latent space. However, recent research highlights that deterministic
  embeddings from standard VLMs often struggle to capture the uncertainties arising
  from the ambiguities in visual and textual descriptions and the multiple possible
  correspondences between images and texts. Existing approaches tackle this by learning
  probabilistic embeddings during VLM training, which demands large datasets and does
  not leverage the powerful representations already learned by large-scale VLMs like
  CLIP. In this paper, we propose GroVE, a post-hoc approach to obtaining probabilistic
  embeddings from frozen VLMs. GroVE builds on Gaussian Process Latent Variable Model
  (GPLVM) to learn a shared low-dimensional latent space where image and text inputs
  are mapped to a unified representation, optimized through single-modal embedding
  reconstruction and cross-modal alignment objectives. Once trained, the Gaussian
  Process model generates uncertainty-aware probabilistic embeddings. Evaluation shows
  that GroVE achieves state-of-the-art uncertainty calibration across multiple downstream
  tasks, including cross-modal retrieval, visual question answering, and active learning.
software: https://github.com/cvjena/GroVE-Probabilistic_VLM_embeddings.git
openreview: dU849kBes4
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: venkataramanan25a
month: 0
tex_title: 'Probabilistic Embeddings for Frozen Vision-Language Models: Uncertainty
  Quantification with Gaussian Process Latent Variable Models'
firstpage: 4309
lastpage: 4328
page: 4309-4328
order: 4309
cycles: false
bibtex_author: Venkataramanan, Aishwarya and Bodesheim, Paul and Denzler, Joachim
author:
- given: Aishwarya
  family: Venkataramanan
- given: Paul
  family: Bodesheim
- given: Joachim
  family: Denzler
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/venkataramanan25a/venkataramanan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
