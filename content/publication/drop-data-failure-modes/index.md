---
title: 'Approximations to worst-case data dropping: unmasking failure modes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jenny Y. Huang
  - David R. Burt
  - admin
  - Yunyi Shen
  - Tamara Broderick

# Author notes (optional)
author_notes:

date: '2024-08-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: 'A data analyst might worry about generalization if dropping a very small fraction of data points from a study could change its substantive conclusions. Finding the worst-case data subset to drop poses a combinatorial optimization problem. To overcome this intractability, recent works propose using additive approximations, which treat the contribution of a collection of data points as the sum of their individual contributions, and greedy approximations, which iteratively select the point with the highest impact to drop and re-run the data analysis without that point [Broderick et al., 2020, Kuschnig et al., 2021]. We identify that, even in a setting as simple as OLS linear regression, many of these approximations can break down in realistic data arrangements. Several of our examples reflect masking, where one outlier may hide or conceal the effect of another outlier. Based on the failures we identify, we provide recommendations for users and suggest directions for future improvements.'

# Summary. An optional shortened abstract.
summary: 

tags: ["Influence Function"]

# Display this page in the Featured widget?
featured: 

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2408.09008'
url_code: ''
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
