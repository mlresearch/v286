---
title: A Probabilistic Neuro-symbolic Layer for Algebraic Constraint Satisfaction
abstract: In safety-critical applications, guaranteeing the satisfaction of constraints
  over continuous environments is crucial, e.g., an autonomous agent should never
  crash over obstacles or go off-road. Neural models struggle in the presence of these
  constraints, especially when they involve intricate algebraic relationships. To
  address this, we introduce a differentiable probabilistic layer that guarantees
  the satisfaction of non-convex algebraic constraints over continuous variables.
  This probabilistic algebraic layer (PAL) can be seamlessly plugged into any neural
  architecture and trained via maximum likelihood without requiring approximations.
  PAL defines a distribution over conjunctions and disjunctions of linear inequalities,
  parametrized by polynomials. This formulation enables efficient and exact renormalization
  via symbolic integration, which can be amortized across different data points and
  easily parallelized on a GPU. We showcase PAL and our integration scheme on a number
  of benchmarks for algebraic constraint integration and on real-world trajectory
  data.
software: https://github.com/april-tools/pal
openreview: 9UkxftKU4I
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kurscheidt25a
month: 0
tex_title: A Probabilistic Neuro-symbolic Layer for Algebraic Constraint Satisfaction
firstpage: 2431
lastpage: 2471
page: 2431-2471
order: 2431
cycles: false
bibtex_author: Kurscheidt, Leander and Morettin, Paolo and Sebastiani, Roberto and
  Passerini, Andrea and Vergari, Antonio
author:
- given: Leander
  family: Kurscheidt
- given: Paolo
  family: Morettin
- given: Roberto
  family: Sebastiani
- given: Andrea
  family: Passerini
- given: Antonio
  family: Vergari
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/kurscheidt25a/kurscheidt25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
