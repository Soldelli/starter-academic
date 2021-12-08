---
title: "MAD: A Scalable Dataset for Language Grounding in Videos from Movie
  Audio Descriptions"
subtitle: ""
publication_types:
  - "3"
authors:
  - admin
  - Mengmeng Xu
  - Sisi Qu
  - Jesper Tegner
  - Bernard Ghanem
author_notes:
  - Equal contribution
  - Equal contribution
  - Equal contribution
doi: ""
publication: In *Workshop of International Conference on Computer Vision*
publication_short: In *ICCVW*
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
featured: true
tags: []
projects:
  - VLG-Net
image:
  focal_point: Smart
  preview_only: false
summary: ""
date: 2021-12-08T12:47:11.855Z
links:
  - name: Preprint
    url: https://arxiv.org/abs/2011.10132
  - name: PDF
    url: https://openaccess.thecvf.com/content/ICCV2021W/CVEU/papers/Soldan_VLG-Net_Video-Language_Graph_Matching_Network_for_Video_Grounding_ICCVW_2021_paper.pdf
  - name: Supplementary Material
    url: https://openaccess.thecvf.com/content/ICCV2021W/CVEU/supplemental/Soldan_VLG-Net_Video-Language_Graph_ICCVW_2021_supplemental.pdf
  - name: Code
    url: https://github.com/Soldelli/VLG-Net
  - name: Video
    url: https://www.youtube.com/watch?v=u9IwxnDCb68
publishDate: 2021-08-17T00:00:00Z
---

**BibTex**

```
@inproceedings{soldan2021vlg,
  title={VLG-Net: Video-Language Graph Matching Network for Video Grounding},
  author={Soldan, Mattia and Xu, Mengmeng and Qu, Sisi and Tegner, Jesper and Ghanem, Bernard},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={3224--3234},
  year={2021}
}
```
