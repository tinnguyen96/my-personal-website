---
title: 'Sensitivity of MCMC-based analyses to small-data removal'

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

date: '2024-08-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: If the conclusion of a data analysis is sensitive to dropping very few data points, that conclusion might hinge on the particular data at hand rather than representing a more broadly applicable truth. How could we check whether this sensitivity holds? One idea is to consider every small subset of data, drop it from the dataset, and re-run our analysis. But running MCMC to approximate a Bayesian posterior is already very expensive; running multiple times is prohibitive, and the number of re-runs needed here is combinatorially large. Recent work proposes a fast and accurate approximation to find the worst-case dropped data subset, but that work was developed for problems based on estimating equations -- and does not directly handle Bayesian posterior approximations using MCMC. We make two principal contributions in the present work. We adapt the existing data-dropping approximation to estimators computed via MCMC. Observing that Monte Carlo errors induce variability in the approximation, we use a variant of the bootstrap to quantify this uncertainty. We demonstrate how to use our approximation in practice to determine whether there is non-robustness in a problem. Empirically, our method is accurate in simple models, such as linear regression. In models with complicated structure, such as hierarchical models, the performance of our method is mixed.

# Summary. An optional shortened abstract.
summary:

tags: ["Markov chain Monte Carlo", "Bayesian Statistics", "Influence Function"]

# Display this page in the Featured widget?
featured: 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2408.07240'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://arxiv.org/abs/2408.07240'
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
slides: uploads/mcmc-amip/slides.pdf
---
