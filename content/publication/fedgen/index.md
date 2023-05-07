---
title: "Data-Free Knowledge Distillation for Heterogeneous Federated Learning"
date: "2021-06-02T13:08:20+08:00"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Junyuan Hong
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
publication: Proceedings of the 38 th International Conference on Machine Learning
publication_short: ICML

# Abstract and optional shortened version.
abstract: Federated Learning (FL) is a decentralized machine-learning paradigm, in which a global server iteratively averages the model parameters of local users without accessing their data. User heterogeneity has imposed significant challenges to FL, which can incur drifted global models that are slow to converge. Knowledge Distillation has recently emerged to tackle this issue, by refining the server model using aggregated knowledge from heterogeneous users, other than directly averaging their model parameters. This approach, however, depends on a proxy dataset, making it impractical unless such a prerequisite is satisfied. Moreover, the ensemble knowledge is not fully utilized to guide local model learning, which may in turn affect the quality of the aggregated model. Inspired by the prior art, we propose a data-free knowledge distillation approach to address heterogeneous FL, where the server learns a lightweight generator to ensemble user information in a data-free manner, which is then broadcasted to users, regulating local training using the learned knowledge as an inductive bias. Empirical studies powered by theoretical implications show that our approach facilitates FL with better generalization performance using fewer communication rounds, compared with the state-of-the-art.

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
tags: ["Federated learning", "Data-Heterogeneity", "Non-IID"]
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
