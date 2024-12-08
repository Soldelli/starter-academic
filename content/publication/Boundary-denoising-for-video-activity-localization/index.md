---
title: "Boundary-denoising for video activity localization"
subtitle: ''

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Mengmeng Xu
- admin
- Jialin Gao 
- Shuming Liu 
- Juan-Manuel Pérez-Rúa
- Bernard Ghanem

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-04-01T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.

publication: In Proceedings of the *International Conference on Learning Representations* (ICLR)
publication_short: In *ICLR*

abstract: "Video activity localization aims at understanding the semantic content in long untrimmed videos and retrieving actions of interest. The retrieved action with its start and end locations can be used for highlight generation, temporal action detection, etc. Unfortunately, learning the exact boundary location of activities is highly challenging because temporal activities are continuous in time, and there are often no clear-cut transitions between actions. Moreover, the definition of the start and end of events is subjective, which may confuse the model. To alleviate the boundary ambiguity, we propose to study the video activity localization problem from a denoising perspective. Specifically, we propose an encoder-decoder model named DenoiseLoc. During training, a set of action spans is randomly generated from the ground truth with a controlled noise scale. Then we attempt to reverse this process by boundary denoising, allowing the localizer to predict activities with precise boundaries and resulting in faster convergence speed. Experiments show that DenoiseLoc advances %in several video activity understanding tasks. For example, we observe a gain of +12.36% average mAP on QV-Highlights dataset and +1.64% mAP@0.5 on THUMOS'14 dataset over the baseline. Moreover, DenoiseLoc achieves state-of-the-art performance on TACoS and MAD datasets, but with much fewer predictions compared to other current methods."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/2304.02934
- name: PDF
  url: https://arxiv.org/pdf/2304.02934
- name: Supplementary Material
  url: ''
- name: Code
  url: https://github.com/frostinassiky/denoiseloc
# - name: Video
#   url: 'https://webcast.kaust.edu.sa/Mediasite/Showcase/default/Presentation/88b31db635ba445bb5fcbf43f7d5136f1d'


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
- DenoiseLoc



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@article{xu2023boundary,
  title={Boundary-denoising for video activity localization},
  author={Xu, Mengmeng and Soldan, Mattia and Gao, Jialin and Liu, Shuming and P{\'e}rez-R{\'u}a, Juan-Manuel and Ghanem, Bernard},
  journal={arXiv preprint arXiv:2304.02934},
  year={2023}
}
```
