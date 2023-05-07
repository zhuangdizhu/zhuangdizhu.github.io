---
title: "Self-Adaptive Imitation Learning: Learning Tasks with Delayed Rewards from Sub-Optimal Demonstrations."
date: "2022-06-02T13:08:20+08:00"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Kaixiang Lin
- Bo Dai
- Jiayu Zhou
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types: ["1"]

# Publication name and optional abbreviated version.
publication: Proceedings of the 36-th AAAI Conference on Artificial Intelligence
publication_short: AAAI

# Abstract and optional shortened version.
abstract: Reinforcement learning (RL) has demonstrated its superiority in solving sequential decision-making problems. However, heavy dependence on immediate reward feedback impedes the wide application of RL. On the other hand, imitation learning (IL) tackles RL without relying on environmental supervision by leveraging external demonstrations. In practice, however, collecting sufficient expert demonstrations can be prohibitively expensive, yet the quality of demonstrations typically limits the performance of the learning policy. To address a practical scenario, in this work, we propose SelfAdaptive Imitation Learning (SAIL), which, provided with a few demonstrations from a sub-optimal teacher, can perform well in RL tasks with extremely delayed rewards, where the only reward feedback is trajectory-wise ranking. SAIL bridges the advantages of IL and RL by interactively exploiting the demonstrations to catch up with the teacher and exploring the environment to yield demonstrations that surpass the teacher. Extensive empirical results show that not only does SAIL significantly improve the sample efficiency, but it also leads to higher asymptotic performance across different continuous control tasks, compared with the state-of-the-art.

# Featured image thumbnail (optional)
image_preview: ""

# Is this a selected publication? (true/false)
selected: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
# projects: ["deep-learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags: ["Imitation Learning", "Learning from Suboptimal Knowledge", "Exploration in RL", "Self-Adaptative Learning"]
featured: true

# Links (optional).
url_pdf: "http://proceedings.mlr.press/v139/zhu21b/zhu21b.pdf"
url_preprint: ""
url_code: "https://github.com/zhuangdizhu/FedGen"
url_dataset: ""
url_project: ""
url_slides: ""
url_video: "https://crossminds.ai/video/data-free-knowledge-distillation-for-heterogeneous-federated-learning-614bca2f3c7a224a90902919/"
url_poster: ""
url_source: ""


# Does this page contain LaTeX math? (true/false)
math: false

# Does this page require source code highlighting? (true/false)
highlight: true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
image:
  caption: 'FedGen'
  focal_point: "left"
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - "federated-learning"

---
