---
title: Transfer Learning for Car-Racing Environments
summary: Model-free & model-based transfer learning for car-racing.
tags:
  - ML
date: '2022-04-24T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Gym Car Racing Environment
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/benedictflorance/carracing-transfer-learning'
url_pdf: 'https://drive.google.com/file/d/1ff7ltKgtPg3Zh_OPmRL3BGPSiANHvkXO/view?usp=sharing'
url_slides: 'https://docs.google.com/presentation/d/1DRtoCZ1fpw1gibMQfuqbHETs9g_qIWkJ2238V0Yx5h4/edit?usp=sharing'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- Used transfer learning to achieve the fast lap times in OpenAI’s Car racing environment by training the agent on one circuit, and racing it on other
customized target environments by zero-shot transfer or by additional fine-tuning. 
- Compared the performance of
model-based and model-free approaches, and observed that model-based approaches dominate in performance and converge
faster than model-free approaches in this environment.
- Observed that transfer learning in most setups not only boosts the
performance on the target domain, but also shows high performance ability during learning.