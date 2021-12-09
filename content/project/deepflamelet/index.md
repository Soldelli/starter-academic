---
title: "Large eddy simulation with flamelet progress variable approach combined with artificial neural network acceleration"
subtitle: 'Cross-department collaboration for Deep Learning application to Flames simulations.'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Lorenzo Angelilli
- Pietro Paolo Ciottoli
- Riccardo Malpica Galassi
- Francisco E. Hernandez Perez
- admin
- Zhen Lu
- Mauro Valorani
- Hong G. Im

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-04T11:00:43.124Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-04T11:00:43.124Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *American Institute of Aeronautics and Astronautics*
publication_short: In *AIAA SciTech*

abstract: "In the context of large eddy simulation of turbulent reacting flows, flamelet-based models are key to affordable simulations of large and complex systems. However, as the complexity of the problem increases, higher-dimensional look-up tables are required, rendering the conventional look-up procedure too demanding. This work focuses on accelerating the estimation of flamelet- based data for the flamelet/progress variable model via an artificial neural network. The neural network hyper-parameters are defined by a Bayesian optimization and two different architectures are selected for comparison against the classical look-up procedure on the well known Sandia flame D. The performance in terms of execution time and accuracy are analyzed, showing that the neural network model reduces the computational time by 30%, as compared to the traditional table look-up, while retaining comparable accuracy."

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: PDF
  url: https://arc.aiaa.org/doi/pdf/10.2514/6.2021-0412


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
- DeepFlamelet



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

**BibTex**

```
@inproceedings{angelilli2021large,
  title={Large eddy simulation with flamelet progress variable approach combined with artificial neural network acceleration},
  author={Angelilli, Lorenzo and Ciottoli, Pietro Paolo and Malpica Galassi, Riccardo and Hernandez Perez, Francisco E and Soldan, Mattia and Lu, Zhen and Valorani, Mauro and Im, Hong G},
  booktitle={AIAA Scitech 2021 Forum},
  pages={0412},
  year={2021}
}
```
