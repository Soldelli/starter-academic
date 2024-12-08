---
title: "OpenTAD: An Open-Source Toolbox for Temporal Action Detection"
summary: "OpenTAD is an open-source temporal action detection (TAD) toolbox based on PyTorch developed for fostering reproducible open research."
tags:
date: "2024-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/sming256/OpenTAD"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

- Support SoTA TAD methods with modular design. We decompose the TAD pipeline into different components, and implement them in a modular way. This design makes it easy to implement new methods and reproduce existing methods.
- Support multiple TAD datasets. We support 9 TAD datasets, including ActivityNet-1.3, THUMOS-14, HACS, Ego4D-MQ, EPIC-Kitchens-100, FineAction, Multi-THUMOS, Charades, and EPIC-Sounds Detection datasets.
- Support feature-based training and end-to-end training. The feature-based training can easily be extended to end-to-end training with raw video input, and the video backbone can be easily replaced.
- Release various pre-extracted features. We release the feature extraction code, as well as many pre-extracted features on each dataset.