---
title: 'Epistemic Uncertainty in Conformal Scores: A Unified Approach'
abstract: Conformal prediction methods create prediction bands with distribution-free
  guarantees but do not explicitly capture epistemic uncertainty, which can lead to
  overconfident predictions in data-sparse regions. Although recent conformal scores
  have been developed to address this limitation, they are typically designed for
  specific tasks, such as regression or quantile regression. Moreover, they rely on
  particular modeling choices for epistemic uncertainty, restricting their applicability.
  We introduce $\texttt{EPICSCORE}$, a model-agnostic approach that enhances any conformal
  score by explicitly integrating epistemic uncertainty. Leveraging Bayesian techniques
  such as Gaussian Processes, Monte Carlo Dropout, or Bayesian Additive Regression
  Trees, $\texttt{EPICSCORE}$ adaptively expands predictive intervals in regions with
  limited data while maintaining compact intervals where data is abundant. As with
  any conformal method, it preserves finite-sample marginal coverage. Additionally,
  it also achieves asymptotic conditional coverage. Experiments demonstrate its good
  performance compared to existing methods. Designed for compatibility with any Bayesian
  model, but equipped with distribution-free guarantees, $\texttt{EPICSCORE}$ provides
  a general-purpose framework for uncertainty quantification in prediction problems.
software: https://github.com/Monoxido45/EPICSCORE
openreview: 8JqNv79BR0
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cruz-cabezas25a
month: 0
tex_title: 'Epistemic Uncertainty in Conformal Scores: A Unified Approach'
firstpage: 443
lastpage: 470
page: 443-470
order: 443
cycles: false
bibtex_author: Cruz Cabezas, Luben Miguel and Silva Santos, Vagner and Ramos, Thiago
  and Izbicki, Rafael
author:
- given: Luben Miguel
  family: Cruz Cabezas
- given: Vagner
  family: Silva Santos
- given: Thiago
  family: Ramos
- given: Rafael
  family: Izbicki
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/cruz-cabezas25a/cruz-cabezas25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
