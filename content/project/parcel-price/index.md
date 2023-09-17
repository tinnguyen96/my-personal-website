---
title: Parcel Price Prediction
summary: Build supervised learning model and evaluate accuracy for predicting Boston property prices.
tags: ["Supervised Learning", "Gradient Boosting Machine", "Real Estate"]

date: '2023-09-12T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Median Housing Price in Each Boston Zipcode circa 2019. Obtained from https://simplemaps.com/city/boston/zips/home-value.
  focal_point: Smart

url_code: 'https://github.com/tinnguyen96/boston-parcel-price'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Using [Boston’s property assessment data](https://data.boston.gov/dataset/property-assessment), I built a prediction system for the price of a land parcel using its physical attributes. 
Stakeholders who might use the predictions are the city of Boston itself (to determine property tax) and homeowners (to find a fair value for their purchase).
I used pandas to manipulate csvs, sklearn to preprocess (removing outliers, imputing missing features) and cross-validate, and finall LightGBM to fit learner. 
On single-household residences, the system is reasonably accurate: the average absolute percentage error is about 25%. 
The most important predictive feature is the total living area.
