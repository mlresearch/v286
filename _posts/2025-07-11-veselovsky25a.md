---
title: 'Hindsight Merging: Diverse Data Generation with Language Models'
abstract: Pre-training a language model equips it with a broad understanding of the
  world, while fine- tuning refines it into a helpful assistant. However, fine-tuning
  does not exclusively enhance task- specific behaviors but also suppresses some of
  the beneficial variability from pre-training. This reduction in diversity is partly
  due to the optimization process, which theoretically decreases model entropy in
  exchange for task performance. To counteract this, we introduce hindsight merging,
  a technique that combines a fine-tuned model with a previous training checkpoint
  using linear interpolation to restore entropy and improve performance. Hindsight-merged
  models retain strong instruction-following capabilities and alignment while displaying
  increased diversity present in the base model. Additionally, this results in improved
  inference scaling, achieving a consistent 20-50% increase in pass@10 relative to
  the instruction tuned model across a coding benchmark and series of models. Our
  findings suggest that hindsight merging is an effective strategy for generating
  diverse generations that follow instructions.
software: https://github.com/benediktstroebl/hindsight-merging
openreview: gvsdQ72Peg
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: veselovsky25a
month: 0
tex_title: 'Hindsight Merging: Diverse Data Generation with Language Models'
firstpage: 4349
lastpage: 4369
page: 4349-4369
order: 4349
cycles: false
bibtex_author: Veselovsky, Veniamin and Stroebl, Benedikt and Bencomo, Gianluca and
  Arumugam, Dilip and Schut, Lisa and Narayanan, Arvind and Griffiths, Thomas L.
author:
- given: Veniamin
  family: Veselovsky
- given: Benedikt
  family: Stroebl
- given: Gianluca
  family: Bencomo
- given: Dilip
  family: Arumugam
- given: Lisa
  family: Schut
- given: Arvind
  family: Narayanan
- given: Thomas L.
  family: Griffiths
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
pdf: https://raw.githubusercontent.com/mlresearch/v286/main/assets/veselovsky25a/veselovsky25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
