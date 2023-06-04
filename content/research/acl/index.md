---
title: Linguistic Properties of Truthful Responses
summary: Truthfulness prediction of LLM's responses using linguistic features.
tags:
  - Deep Learning
  - NLP
date: '2023-05-15T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Linguistic profiles of different GPT models
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: 'https://github.com/benedictflorance/truthfulqa_experiments'
url_pdf: 'https://arxiv.org/abs/2305.15875'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- We investigate the phenomenon of an LLM's untruthful response using a large set of 220 handcrafted linguistic features. We focus on GPT-3 models and find that the linguistic profiles of responses are similar across model sizes. 
- That is, how varying-sized LLMs respond to given prompts stays similar on the linguistic properties level. 
- We expand upon this finding by training support vector machines that rely only upon the stylistic components of model responses to classify the truthfulness of statements. 
- Though the dataset size limits our current findings, we present promising evidence that truthfulness detection is possible without evaluating the content itself.
- This paper was accepted at TrustNLP @ ACL 2023
