---
title: "Independent finite approximations for Bayesian nonparametric inference"
authors:
- admin
- Jonathan Huggins
- Lorenzo Masoero
- Lester Mackey
- Tamara Broderick

author_notes:

date: "2022-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Bayesian nonparametric priors based on completely random measures (CRMs) offer a flexible modeling approach when the number of latent components in a dataset is unknown. However, managing the infinite dimensionality of CRMs typically requires practitioners to derive ad-hoc algorithms, preventing the use of general-purpose inference methods and often leading to long compute times. We propose a general but explicit recipe to construct a simple finite-dimensional approximation that can replace the infinite-dimensional CRMs. Our independent finite approximation (IFA) is a generalization of important cases that are used in practice. The independence of atom weights in our approximation (i) makes the construction well-suited for parallel and distributed computation and (ii) facilitates more convenient inference schemes. We quantify the approximation error between IFAs and the target nonparametric prior. We compare IFAs with an alternative approximation scheme -- truncated finite approximations (TFAs), where the atom weights are constructed sequentially. We prove that, for worst-case choices of observation likelihoods, TFAs are a more efficient approximation than IFAs. However, in real-data experiments with image denoising and topic modeling, we find that IFAs perform very similarly to TFAs in terms of task-specific accuracy metrics.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes

# links:
# - name: ""
#   url: ""
url_pdf: "https://arxiv.org/pdf/2009.10780.pdf"
url_code: ""
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: uploads/finite-crm-approximations/slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:

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

