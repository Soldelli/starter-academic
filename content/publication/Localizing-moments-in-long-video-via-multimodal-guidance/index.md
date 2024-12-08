---
title: "Localizing Moments in Long Video via Multimodal Guidance"
subtitle: ''

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Wayner Barrios
- Mattia Soldan 
- Alberto Mario Ceballos-Arroyo
- Fabian Caba Heilbron
- Bernard Ghanem

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2023-12-01T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.

publication: In Proceedings of the IEEE/CVF *International Conference on Computer Vision* (ICCV)
publication_short: In *ICCV*

abstract: "The recent introduction of the large-scale, long-form MAD and Ego4D datasets has enabled researchers to investigate the performance of current state-of-the-art methods for video grounding in the long-form setup, with interesting findings: current grounding methods alone fail at tackling this challenging task and setup due to their inability to process long video sequences. In this paper, we propose a method for improving the performance of natural language grounding in long videos by identifying and pruning out non-describable windows. We design a guided grounding framework consisting of a Guidance Model and a base grounding model. The Guidance Model emphasizes describable windows, while the base grounding model analyzes short temporal windows to determine which segments accurately match a given language query. We offer two designs for the Guidance Model: Query-Agnostic and Query-Dependent, which balance efficiency and accuracy. Experiments demonstrate that our proposed method outperforms state-of-the-art models by 4.1% in MAD and 4.52% in Ego4D (NLQ), respectively."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://openaccess.thecvf.com/content/ICCV2023/html/Barrios_Localizing_Moments_in_Long_Video_Via_Multimodal_Guidance_ICCV_2023_paper.html
- name: PDF
  url: https://openaccess.thecvf.com/content/ICCV2023/papers/Barrios_Localizing_Moments_in_Long_Video_Via_Multimodal_Guidance_ICCV_2023_paper.pdf
- name: Supplementary Material
  url: 'https://openaccess.thecvf.com/content/ICCV2023/supplemental/Barrios_Localizing_Moments_in_ICCV_2023_supplemental.pdf'
- name: Code
  url: https://github.com/waybarrios/guidance-based-video-grounding
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
- Guidance



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@inproceedings{barrios2023localizing,
  title={Localizing moments in long video via multimodal guidance},
  author={Barrios, Wayner and Soldan, Mattia and Ceballos-Arroyo, Alberto Mario and Heilbron, Fabian Caba and Ghanem, Bernard},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={13667--13678},
  year={2023}
}
```
