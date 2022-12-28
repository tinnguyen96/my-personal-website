---
title: 'Measuring the robustness of Gaussian processes to kernel choice'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - William T. Stephenson
  - Soumya Ghosh
  - admin
  - Mikhail Yurochkin
  - Sameer K. Deshpande
  - Tamara Broderick

# Author notes (optional)
author_notes:

date: '2022-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Artificial Intelligence and Statistics 2022
publication_short: In *AISTATS 2022*

abstract: Gaussian processes (GPs) are used to make medical and scientific decisions, including in cardiac care and monitoring of atmospheric carbon dioxide levels. Notably, the choice of GP kernel is often somewhat arbitrary. In particular, uncountably many kernels typically align with qualitative prior knowledge (e.g.\ function smoothness or stationarity). But in practice, data analysts choose among a handful of convenient standard kernels (e.g.\ squared exponential). In the present work, we ask:Would decisions made with a GP differ under other, qualitatively interchangeable kernels? We show how to answer this question by solving a constrained optimization problem over a finite-dimensional space. We can then use standard optimizers to identify substantive changes in relevant decisions made with a GP. We demonstrate in both synthetic and real-world examples that decisions made with a GP can exhibit non-robustness to kernel choice, even when prior draws are qualitatively interchangeable to a user.

# Summary. An optional shortened abstract.
summary:

tags: ["Gaussian process", "robustness"]

# Display this page in the Featured widget?
featured: 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2106.06510.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
