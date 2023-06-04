---
title: Unsupervised Deep Domain Adaption for Object Detection
summary:  Analysis of the current image-to-image adpation methods on video-surveillance datasets.

tags:
  - Deep Learning
  - Computer Vision
date: '2019-08-15T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Foggy Cityscape Dataset
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://drive.google.com/file/d/1hOYt2EsUJPyBWioX0BRrLYqUi2XEDD5Y/view'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
- Analyzed negative transfer (around 20% drop in mAP from baseline) and catastrophic forgetting of the existing imageto-image domain adaptation approaches on face-detection datasets.
- Studied the use of local features, and temporal
information from trackers to generalize unsupervised domain adaptation approaches on datasets like SCUT and Widerface.
- **Advisor:** [Eric Granger](https://www.etsmtl.ca/en/research/professors/egranger)