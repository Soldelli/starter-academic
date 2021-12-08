---
title: "VLG-Net: Video-Language Graph Matching Network for Video Grounding"
subtitle: Best Paper Award
publication_types:
  - "1"
authors:
  - Mattia Soldan
  - Mengmeng Xu
  - Sisi Qu
  - Jesper Tegner
  - Bernard Ghanem
publication: Workshop of International Conference on Computer Vision
abstract: "Grounding language queries in videos aims at identifying the time
  interval (or moment) semantically relevant to a language query. The solution
  to this challenging task demands understanding videos' and queries' semantic
  content and the fine-grained reasoning about their multi-modal interactions.
  Our key idea is to recast this challenge into an algorithmic graph matching
  problem. Fueled by recent advances in Graph Neural Networks, we propose to
  leverage Graph Convolutional Networks to model video and textual information
  as well as their semantic alignment. To enable the mutual exchange of
  information across the modalities, we design a novel Video-Language Graph
  Matching Network (VLG-Net) to match video and query graphs. Core ingredients
  include representation graphs built atop video snippets and query tokens
  separately and used to model intra-modality relationships. A Graph Matching
  layer is adopted for cross-modal context modeling and multi-modal fusion.
  Finally, moment candidates are created using masked moment attention pooling
  by fusing the moment's enriched snippet features. We demonstrate superior
  performance over state-of-the-art grounding methods on three widely used
  datasets for temporal localization of moments in videos with language queries:
  ActivityNet-Captions, TACoS, and DiDeMo."
draft: false
featured: true
projects:
  - VLG-Net
image:
  filename: vlg-net.png
  focal_point: Smart
  preview_only: false
date: 2021-12-08T11:00:43.124Z
---
BibTex

@inproceedings{soldan2021vlg,
  title={VLG-Net: Video-Language Graph Matching Network for Video Grounding},
  author={Soldan, Mattia and Xu, Mengmeng and Qu, Sisi and Tegner, Jesper and Ghanem, Bernard},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={3224--3234},
  year={2021}
}