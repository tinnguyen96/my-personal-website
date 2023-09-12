---
title: "Independent finite approximations for Bayesian nonparametric inference"
authors:
- admin
- Jonathan Huggins
- Lorenzo Masoero
- Lester Mackey
- Tamara Broderick

author_notes:

date: "2023-05-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bayesian Analysis Advance Publication"
publication_short: "Bayesian Analysis Advance Publication"

abstract: Completely random measures (CRMs) and their normalizations (NCRMs) offer flexible models in Bayesian nonparametrics. But their infinite dimensionality presents challenges for inference. Two popular finite approximations are truncated finite approximations (TFAs) and independent finite approximations (IFAs). While the former have been well-studied, IFAs lack similarly general bounds on approximation error, and there has been no systematic comparison between the two options. In the present work, we propose a general recipe to construct practical finite-dimensional approximations for homogeneous CRMs and NCRMs, in the presence or absence of power laws. We call our construction the automated independent finite approximation (AIFA). Relative to TFAs, we show that AIFAs facilitate more straightforward derivations and use of parallel computing in approximate inference. We upper bound the approximation error of AIFAs for a wide class of common CRMs and NCRMs — and thereby develop guidelines for choosing the approximation level. Our lower bounds in key cases suggest that our upper bounds are tight. We prove that, for worst-case choices of observation likelihoods, TFAs are more efficient than AIFAs. Conversely, we find that in real-data experiments with standard likelihoods, AIFAs and TFAs perform similarly. Moreover, we demonstrate that AIFAs can be used for hyperparameter estimation even when other potential IFA options struggle or do not apply.

# Summary. An optional shortened abstract.
summary: 

tags: ["Bayesian Statistics", "Nonparametric", "Unsupervised Learning", "Topic Models"]

# links:
# - name: ""
#   url: ""
url_pdf: "https://projecteuclid.org/journals/bayesian-analysis/advance-publication/Independent-Finite-Approximations-for-Bayesian-Nonparametric-Inference/10.1214/23-BA1385.full"
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

