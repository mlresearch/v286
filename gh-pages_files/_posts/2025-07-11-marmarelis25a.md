---
title: Off-policy Predictive Control with Causal Sensitivity Analysis
abstract: Predictive models are often deployed for decision-making tasks for which
  they were not explicitly trained. When only partial observations of the relevant
  state are available, as in most real-world applications, there is a strong possibility
  of hidden confounding. Therefore, partial observability often makes the outcome
  of an action unidentifiable, and could render a model’s predictions unreliable for
  action planning. We present an identification bound and propose an algorithm to
  account for hidden confounding during model-predictive control. To that end, we
  introduce a generalized causal sensitivity model for action-state dynamics. We place
  a constraint on the hidden confounding between trajectories of future actions and
  states, enabling sharp bounds on interventional outcomes. Unlike previous sensitivity
  models, ours accommodates hidden confounding with memory, while maintaining computational
  and statistical tractability. We benchmark on a wide variety of multivariate stochastic
  differential equations with arbitrary confounding. The results suggest that a calibrated
  sensitivity model helps controllers achieve higher rewards.
openreview: OQHNq1k0GN
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: marmarelis25a
month: 0
tex_title: Off-policy Predictive Control with Causal Sensitivity Analysis
firstpage: 2958
lastpage: 2972
page: 2958-2972
order: 2958
cycles: false
bibtex_author: Marmarelis, Myrl G and Hasan, Ali and Azizzadenesheli, Kamyar and Alvarez,
  R. Michael and Anandkumar, Anima
author:
- given: Myrl G
  family: Marmarelis
- given: Ali
  family: Hasan
- given: Kamyar
  family: Azizzadenesheli
- given: R. Michael
  family: Alvarez
- given: Anima
  family: Anandkumar
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/marmarelis25a/marmarelis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
