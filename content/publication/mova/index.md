---
title: "MoVA: Learning Asymmetric Dual Projections for Modular Long Video‑Text Alignment"
authors:
- peiyuan_zhu
- shaoan_xie
- zijian_li
- yifan_shen
- admin
- harsh_shrivastava
- guangyi_chen
- kun_zhang
date: "2026-09-08T14:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "19th European Conference on Computer Vision (ECCV)"
publication_short: ""

# abstract: Contrastive pre-training has propelled video-text alignment, yet models often inherit the critical limitations of their image-text predecessors like CLIP, resulting in entangled representations. These challenges are severely exacerbated by two fundamental properties in the video domain: Temporal Misalignment, where textual descriptions often correlate only to specific, constrained temporal windows, leaving other frames text-irrelevant; and Semantic Asymmetry, which dictates a sparse, bidirectional, and non-equivalent relevance between frame-level visual details and caption-level concepts. This failure persists whether captions are short and temporally disjoint, creating ambiguity, or long and detailed, fostering entanglement between static objects and their temporal evolution. In this paper, we establish theoretical conditions that enable flexible alignment between video and text representations across the temporal dimension and at varying levels of granularity. Building on these theoretical insights, we introduce MoVA, Modular Long Video-Text Alignment, which learns dual asymmetric projections: a text-side projection that adaptively selects frame-aware subspaces of the caption, and a video-side projection that disentangles text-relevant visual concepts. Our framework ensures that the model can preserve global cross-modal semantics while disentangling evolving, frame-specific concepts and scale naturally to long captions and videos. Empirical evaluations show that MoVA outperforms existing methods in multiple video-text alignment tasks, demonstrating the effectiveness of our method.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: OpenReview
#   url: ''
- name: arXiv
  url: https://arxiv.org/abs/2607.00858
# url_pdf: https://arxiv.org/pdf/2607.00858
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
  caption: 'Presented at ECCV 2026.'
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

