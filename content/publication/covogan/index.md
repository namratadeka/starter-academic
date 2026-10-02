---
title: "Controllable Video Generation with Provable Disentanglement"
authors:
- yifan_shen
- peiyuan_zhu
- zijian_li
- shaoan_xie
- admin
- zongfang_liu
- zeyu_tang
- guangyi_chen
- kun_zhang
date: "2026-04-23T14:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "14th International Conference on Learning Representations (ICLR)"
publication_short: ""

# abstract: Controllable video generation remains a significant challenge, despite recent advances in generating high-quality and consistent videos. Most existing methods for controlling video generation treat the video as a whole, neglecting intricate fine-grained spatiotemporal relationships, which limits both control precision and efficiency. In this paper, we propose \textbf{Co}ntrollable \textbf{V}ide\textbf{o} \textbf{G}enerative \textbf{A}dversarial \textbf{N}etworks (\ourmes) to disentangle the video concepts, thus facilitating efficient and independent control over individual concepts. Specifically, following the \textbf{minimal change principle}, we first disentangle static and dynamic latent variables. We then leverage the \textbf{sufficient change property} to achieve component-wise identifiability of dynamic latent variables, enabling independent control over motion and identity. To establish the theoretical foundation, we provide a rigorous analysis demonstrating the identifiability of our approach. Building on these theoretical insights, we design a \textbf{Temporal Transition Module} to disentangle latent dynamics. To enforce the minimal change principle and sufficient change property, we minimize the dimensionality of latent dynamic variables and impose temporal conditional independence. To validate our approach, we integrate this module as a plug-in for GANs. Extensive qualitative and quantitative experiments on various video generation benchmarks demonstrate that our method significantly improves generation quality and controllability across diverse real-world scenarios.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: OpenReview
  url: https://openreview.net/forum?id=OcLNKpcY4J
- name: arXiv
  url: https://arxiv.org/abs/2502.02690
# url_pdf: https://arxiv.org/abs/2502.02690.pdf
# url_code: ''
# url_dataset: '#'
# url_poster: 'publication/mmd-b-fair/poster.png'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Presented at ICLR 2026.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

