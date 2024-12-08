---
title: "Finding Moments in Video Collections Using Natural Language"
subtitle: ''

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Victor Escorcia
- admin
- Josef Sivic
- Bernard Ghanem 
- Bryan Russell

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-07-30T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *ArXiv*
publication_short: In *ArXiv*

abstract: "In this paper, we introduce the task of retrieving relevant video moments from a large corpus of untrimmed, unsegmented videos given a natural language query. Our task poses unique challenges as a system must efficiently identify both the relevant videos and localize the relevant moments in the videos. This task is in contrast to prior work that localizes relevant moments in a single video or searches a large collection of already-segmented videos. For our task, we introduce Clip Alignment with Language (CAL), a model that aligns features for a natural language query to a sequence of short video clips that compose a candidate moment in a video. Our approach goes beyond prior work that aggregates video features over a candidate moment by allowing for finer clip alignment. Moreover, our approach is amenable to efficient indexing of the resulting clip-level representations, which makes it suitable for moment localization in large video collections. We evaluate our approach on three recently proposed datasets for temporal localization of moments in video with natural language extended to our video corpus moment retrieval setting: DiDeMo, Charades-STA, and ActivityNet-captions. We show that our CAL model outperforms the recently proposed Moment Context Network (MCN) on all criteria across all datasets on our proposed task, obtaining an 8%-85% and 11%-47% boost for average recall and median rank, respectively, and achieves 5x faster retrieval and 8x smaller index size with a 500K video corpus."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Preprint
  url: https://arxiv.org/abs/1907.12763
- name: PDF
  url: https://arxiv.org/pdf/1907.12763.pdf
- name: Supplementary Material
  url: ''
- name: Code
  url: https://github.com/escorciav/moments-retrieval
- name: Video
  url: 'http://bit.ly/3nnDrF9'


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
- STAL



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@misc{escorcia2019temporal,
      title={Temporal Localization of Moments in Video Collections with Natural Language}, 
      author={Victor Escorcia and Mattia Soldan and Josef Sivic and Bernard Ghanem and Bryan Russell},
      year={2019},
      eprint={1907.12763},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
