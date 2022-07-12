---
title: "Egocentric Video-Language Pretraining"
subtitle: ''

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Kevin Qinghong Lin
- Alex Jinpeng Wang
- admin
- Michael Wray
- Rui Yan
- Eric Zhongcong Xu
- Difei Gao
- Rongcheng Tu
- Wenzhe Zhao
- Weijie Kong
- Chengfei Cai
- Hongfa Wang
- Dima Damen
- Bernard Ghanem
- Wei Liu
- Mike Zheng Shou

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-01T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: "Video-Language Pretraining (VLP), aiming to learn transferable representation to advance a wide range of video-text downstream tasks, has recently received increasing attention. Dominant works that achieve strong performance rely on large-scale, 3rd-person video-text datasets, such as HowTo100M. In this work, we exploit the recently released Ego4D dataset to pioneer Egocentric VLP along three directions. (i) We create EgoClip, a 1st-person video-text pretraining dataset comprising 3.8M clip-text pairs well-chosen from Ego4D, covering a large variety of human daily activities. (ii) We propose a novel pretraining objective, dubbed as EgoNCE, which adapts video-text contrastive learning to egocentric domain by mining egocentric-aware positive and negative samples. (iii) We introduce EgoMCQ, a development benchmark that is close to EgoClip and hence can support effective validation and fast exploration of our design decisions regarding EgoClip and EgoNCE. Furthermore, we demonstrate strong performance on five egocentric downstream tasks across three datasets: video-text retrieval on EPIC-KITCHENS-100; action recognition on Charades-Ego; and natural language query, moment query, and object state change classification on Ego4D challenge benchmarks. "

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2206.01670
- name: PDF
  url: https://arxiv.org/pdf/2206.01670.pdf
- name: Supplementary Material
  url: ''
- name: Code
  url: https://github.com/showlab/EgoVLP
- name: Video
  url: ''


# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: Smart
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- EgoVLP



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@misc{https://doi.org/10.48550/arxiv.2206.01670,
  doi = {10.48550/ARXIV.2206.01670},
  url = {https://arxiv.org/abs/2206.01670},
  author = {Lin, Kevin Qinghong and Wang, Alex Jinpeng and Soldan, Mattia and Wray, Michael and Yan, Rui and Xu, Eric Zhongcong and Gao, Difei and Tu, Rongcheng and Zhao, Wenzhe and Kong, Weijie and Cai, Chengfei and Wang, Hongfa and Damen, Dima and Ghanem, Bernard and Liu, Wei and Shou, Mike Zheng},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Artificial Intelligence (cs.AI), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Egocentric Video-Language Pretraining},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution Non Commercial No Derivatives 4.0 International}
}
```
