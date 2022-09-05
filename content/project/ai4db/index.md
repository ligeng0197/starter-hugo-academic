---
title: "AI4DB: Quickly responding mechanism of validating knobs efficacy for GaussDB."
summary: "Exploiting meta-learning mechanism to enhance model generalization with dynamically changing workload of database, with the aim of decreasing model retraining cost and improving overall knobs evaluation performance."
tags:
  - Machine Learning
  - Deep Learning
  - Database
date: '2022-06-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ""
  focal_point: Smart

links:
  - icon: database
    icon_pack: fas
    name: opengauss webpage
    url: 'https://opengauss.org/en/'
url_code: ''
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

**Supervisor: Hongzhi Wang, Professor in Faculty of Computing, HIT**
Exploiting meta-learning mechanism to enhance model generalization with dynamically changing workload of database, with the aim of decreasing model retraining cost and improving overall knobs evaluation performance.

Specifically, we mainly focus on utilizing gradient-based meta-learning on dataset knobs importance ranking & auto-tuning. Through considering each workload performance tests as a few-data task, we propose a meta-learning knobs importance ranking algorithm aimed at reducing dataset enormous knobs under the constraint of only few accessible attached configuration & performance samples each workload. We also design a differential tree model to leverage meta-learning paradigm for dataset performance evaluation & knobs tuning.
