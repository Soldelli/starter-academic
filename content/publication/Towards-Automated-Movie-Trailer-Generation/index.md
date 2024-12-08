---
title: "Towards Automated Movie Trailer Generation"
subtitle: ''

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Dawit Mureja Argaw
- admin
- Alejandro Pardo 
- Chen Zhao 
- Fabian Caba Heilbron
- Joon Son Chung
- Bernard Ghanem

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2024-04-01T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.

publication: In Proceedings of the IEEE/CVF Conference on *Computer Vision and Pattern Recognition* (CVPR)
publication_short: In *CVPR*

abstract: "Movie trailers are an essential tool for promoting films and attracting audiences. However the process of creating trailers can be time-consuming and expensive. To streamline this process we propose an automatic trailer generation framework that generates plausible trailers from a full movie by automating shot selection and composition. Our approach draws inspiration from machine translation techniques and models the movies and trailers as sequences of shots thus formulating the trailer generation problem as a sequence-to-sequence task. We introduce Trailer Generation Transformer (TGT) a deep-learning framework utilizing an encoder-decoder architecture. TGT movie encoder is tasked with contextualizing each movie shot representation via self-attention while the autoregressive trailer decoder predicts the feature representation of the next trailer shot accounting for the relevance of shots' temporal order in trailers. Our TGT significantly outperforms previous methods on a comprehensive suite of metrics."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://openaccess.thecvf.com/content/CVPR2024/html/Argaw_Towards_Automated_Movie_Trailer_Generation_CVPR_2024_paper.html
- name: PDF
  url: https://openaccess.thecvf.com/content/CVPR2024/papers/Argaw_Towards_Automated_Movie_Trailer_Generation_CVPR_2024_paper.pdf


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
- Trailer



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@inproceedings{argaw2024towards,
  title={Towards Automated Movie Trailer Generation},
  author={Argaw, Dawit Mureja and Soldan, Mattia and Pardo, Alejandro and Zhao, Chen and Heilbron, Fabian Caba and Chung, Joon Son and Ghanem, Bernard},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={7445--7454},
  year={2024}
}
```
