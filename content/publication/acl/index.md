---
title: 'Linguistic Properties of Truthful Responses'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bruce W. Lee
  - Benedict Florance Arockiaraj
  - Helen Jin

# Author notes (optional)
author_notes:

date: '2023-06-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Workshop on Trustworthy Natural Language Processing at the Annual Conference of the Association for Computational Linguistics 2023*
publication_short: In *TrustNLP at ACL 2023*

abstract: We investigate the phenomenon of an LLM's untruthful response using a large set of 220 handcrafted linguistic features. We focus on GPT-3 models and find that the linguistic profiles of responses are similar across model sizes. That is, how varying-sized LLMs respond to given prompts stays similar on the linguistic properties level. We expand upon this finding by training support vector machines that rely only upon the stylistic components of model responses to classify the truthfulness of statements. Though the dataset size limits our current findings, we present promising evidence that truthfulness detection is possible without evaluating the content itself.

# Summary. An optional shortened abstract.
summary: Truthfulness prediction of LLM's responses using linguistic features.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2305.15875'
url_code: 'https://github.com/benedictflorance/truthfulqa_experiments'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Linguistic profiles of different GPT models'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
