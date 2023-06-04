---
title: Ensemble-based Endoscopy Artefact Detection
summary:  Ensemble-based endoscopy video artefact detection.

tags:
  - ML
date: '2020-05-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Model Predictions
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'https://drive.google.com/file/d/1eT_1v3QFFPRbGSSB8xz3Aivu4NmvaqGe/view'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---
- Proposed an ensemble of RetinaNet-based object detectors to localize bounding boxes and predict labels of eight different artefact classes that generalizes to an inter-patient, multi-tissue and a multi-modal corpus of endoscopy video frame data

- The common artefacts of interest that corrupt endoscopy video frames include contrast, saturation, instrument, blood, specularity, blur, imaging artefacts and bubbles.

- Achieved an mAP of 0.3405 improving existing state-of-the-art results

- **Advisor**: [Leela Velusamy](https://www.nitt.edu/home/academics/departments/cse/faculty/leela/)