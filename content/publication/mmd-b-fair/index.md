---
title: "MMD-B-Fair: Learning Fair Representations with Statistical Testing"
# authors:
# - admin
# - Danica J. Sutherland
date: "2022-11-15T14:00:00Z"
# doi: "https://doi.org/10.48550/arXiv.2211.07907"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "MMD-B-Fair"

abstract: We introduce a method, MMD-B-Fair, to learn fair representations of data via kernel two-sample testing. We find neural features of our data where a maximum mean discrepancy (MMD) test cannot distinguish between different values of sensitive attributes, while preserving information about the target. Minimizing the power of an MMD test is more difficult than maximizing it (as done in previous work), because the test threshold's complex behavior cannot be simply ignored. Our method exploits the simple asymptotics of block testing schemes to efficiently find fair representations without requiring the complex adversarial optimization or generative modelling schemes widely used by existing work on fair representation learning. We evaluate our approach on various datasets, showing its ability to "hide" information about sensitive attributes, and its effectiveness in downstream transfer tasks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2211.07907
url_pdf: https://arxiv.org/pdf/2211.07907.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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

