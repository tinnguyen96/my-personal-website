---
title: 'Approximations to worst-case data dropping: unmasking failure modes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jenny Y. Huang
  - David R. Burt
  - Yunyi Shen
  - admin
  - Tamara Broderick

# Author notes (optional)
author_notes:

date: '2024-08-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Transactions of Machine Learning Research
publication_short: TMLR

abstract: 'A data analyst might worry about generalization if dropping a very small fraction of data points from a study could change its substantive conclusions. Checking this non-robustness directly poses a combinatorial optimization problem and is intractable even for simple models and moderate data sizes. Recently various authors have proposed a diverse set of approximations to detect this non-robustness. In the present work, we show that, even in a setting as simple as ordinary least squares (OLS) linear regression, many of these approximations can fail to detect (true) non-robustness in realistic data arrangements. We focus on OLS in the present work due its widespread use and since some approximations work only for OLS. Across our synthetic and real-world data sets, we find that a simple recursive greedy algorithm is the sole algorithm that does not fail any of our tests and also that it can be orders of magnitude faster to run than some competitors.'

# Summary. An optional shortened abstract.
summary: 

tags: ["Influence Function"]

# Display this page in the Featured widget?
featured: 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=m6EQ6YdPXV'
url_code: 'https://github.com/JennyHuang19/DataDroppingFailureModes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 
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
