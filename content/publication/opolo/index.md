---
title: "Off-Policy Imitation Learning from Observations"
date: "2020-06-02T13:08:20+08:00"
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
publication: 34th Conference on Neural Information Processing Systems
publication_short: NuerIPs

# Abstract and optional shortened version.
abstract: Learning from Observations (LfO) is a practical reinforcement learning scenario from which many applications can benefit through the reuse of incomplete resources. Compared to conventional imitation learning (IL), LfO is more challenging because of the lack of expert action guidance. In both conventional IL and LfO, distribution matching is at the heart of their foundation. Traditional distribution matching approaches are sample-costly which depend on on-policy transitions for policy learning. Towards sample-efficiency, some off-policy solutions have been proposed, which, however, either lack comprehensive theoretical justifications or depend on the guidance of expert actions. In this work, we propose a sample-efficient LfO approach which enables off-policy optimization in a principled manner. To further accelerate the learning procedure, we regulate the policy update with an inverse action model, which assists distribution matching from the perspective of mode-covering. Extensive empirical results on challenging locomotion tasks indicate that our approach is comparable with state-of-the-art in terms of both sample-efficiency and asymptotic performance.

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
tags: ["Reinforcement learning", "Sample-Efficiency", "Partial Observability", "Imitation Learning"]
featured: true

# Links (optional).
url_pdf: "https://proceedings.neurips.cc/paper/2020/file/92977ae4d2ba21425a59afb269c2a14e-Paper.pdf"
url_preprint: ""
url_code: "https://github.com/illidanlab/opolo-code"
url_dataset: ""
url_project: ""
url_slides: ""
url_video: "https://crossminds.ai/video/off-policy-imitation-learning-from-observations-606fe63df43a7f2f827c06cb/"
url_poster: ""
url_source: ""


# Does this page contain LaTeX math? (true/false)
math: false

# Does this page require source code highlighting? (true/false)
highlight: true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
image:
  caption: 'Opolo'
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
