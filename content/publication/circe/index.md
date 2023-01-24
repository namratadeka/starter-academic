---
title: "Efficient Conditionally Invariant Representation Learning"
authors:
- roman_pogodin
- admin_star
- yazhe_li
- danica_sutherland
- victor_veitch
- arthur_gretton
date: "2023-05-01T14:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "11th International Conference on Learning Representations (ICLR), Top 5% (Oral Presentation)"
publication_short: ""

# abstract: We introduce the Conditional Independence Regression CovariancE(CIRCE), a measure of conditional independence for multivariate continuous-valued variables. CIRCE applies as a regularizer in settings where we wish to learn neural features φ(X) of data X to estimate a target Y , while being conditionally independent of a distractor Z given Y . Both Z and Y are assumed to be continuous-valued but relatively low dimensional, whereas X and its features may be complex and high dimensional. Relevant settings include domain-invariant learning, fairness, and causal learning. The procedure requires just a single ridge regression from Y to kernelized features of Z, which can be done in advance. It is then only necessary to enforce independence of φ(X) from residuals of this regression, which is possible with attractive estimation properties and consistency guarantees. By contrast, earlier measures of conditional feature dependence require multiple regressions for each step of feature learning, resulting in more severe bias and variance, and greater computational cost. When sufficiently rich features are used, we establish that CIRCE is zero if and only if φ(X) ⊥⊥ Z | Y . In experiments we show superior performance to previous methods on challenging benchmarks, including learning conditionally invariant image features.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: OpenReview
  url: https://openreview.net/forum?id=dJruFeSRym1
- name: arXiv
  url: https://arxiv.org/abs/2212.08645
# url_pdf: https://arxiv.org/pdf/2212.08645v1.pdf
url_code: https://github.com/namratadeka/circe
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

