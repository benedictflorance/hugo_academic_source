---
title: Sensible Universal Adversarial Triggers
summary: Generating sensible universal adversarial triggers that are closer to natural phrases.
tags:
  - Deep Learning
  - NLP
date: '2021-12-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Positive Word Cloud
  focal_point: Smart

links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/jianxiongcai/universal-triggers'
url_pdf: 'https://drive.google.com/file/d/1TP26q6haxN3pZdvIfNWirMdeHEkNVAo2/view?usp=sharing'
url_slides: 'https://drive.google.com/file/d/1GuLkff8B1Qis-2_3u43oLja6Xy2lyxJE/view?usp=sharing'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- Proposed a novel technique combining parts-of-speech filtering and perplexity based loss
function to generate sensible triggers that are
closer to natural phrases. 
- For the task of sentiment analysis on the SST dataset, the method
produced sensible triggers that achieve accura-
cies as low as 4% and 12% for flipping positive to negative predictions and vice-versa. 
- To
build robust models, performed adversarial training using the generated triggers that increases the accuracy of the model from 12% to
48%. 
- Illustrated that adversarial at-
tacks can be made difficult to detect by generating sensible triggers, and to facilitate robust
model development through relevant defenses.