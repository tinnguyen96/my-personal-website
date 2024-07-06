---
title: 'Using gradients to check sensitivity of MCMC-based analyses to removing data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ryan Giordano
  - Rachael Meager
  - Tamara Broderick

# Author notes (optional)
author_notes:

date: '2024-07-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In Differentiable Almost Everything 2024
publication_short: In *DiffAE 2024*

abstract: If the conclusion of a data analysis is sensitive to dropping very few data points, that conclusion might hinge on the particular data at hand rather than representing a more broadly applicable truth. To check for this sensitivity, one idea is to consider every small data subset, drop it, and re-run our analysis. But the number of re-runs needed is combinatorially large. Recent work proposes a differentiable relaxation to find the worst-case subset, but that work was developed for conclusions based on estimating equations --- and does not directly handle Bayesian posterior approximations using MCMC. We make two principal contributions. We adapt the existing data-dropping relaxation to estimators computed via MCMC; in particular, we re-use existing MCMC draws to estimate the necessary derivatives via a covariance relationship. Observing that Monte Carlo errors induce variability in the estimates, we use a variant of the bootstrap to quantify this uncertainty. Empirically, our method is accurate in simple models, such as linear regression. In models with complex structure, such as hierarchies, the performance of our method is mixed.

# Summary. An optional shortened abstract.
summary:

tags: ["Markov chain Monte Carlo", "Bayesian Statistics" ]

# Display this page in the Featured widget?
featured: 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=bCPhVcq9Mj'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: uploads/mcmc-amip/slides.pdf
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
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
