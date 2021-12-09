---
title: Seq2Seq RNN based gait anomaly detection from smartphone acquired multimodal motion data
summary: Investigation of encoding strategies for Wireless Sensor Network data to prolong information persistence in the context of battery-powered devices.
tags:
date: "2019-11-09T00:00:00Z"

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
url_code: "https://github.com/Soldelli/gait_anomaly_detection"
url_pdf: https://arxiv.org/pdf/1911.08608.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Smartphones and wearable devices are fast-growing technologies that, in conjunction with advances in wireless sensor hardware, are enabling ubiquitous sensing applications. Wearables are suitable for indoor and outdoor scenarios, can be placed on many parts of the human body, and can integrate a large number of sensors capable of gathering physiological and behavioral biometric information. Here, we are concerned with gait analysis systems that extract meaningful information from users' movements to identify anomalies and changes in their walking style. The solution that is put forward is subject-specific, as the designed feature extraction and classification tools are trained on the subject under observation. A smartphone mounted on an ad-hoc made chest support is utilized to gather inertial data and video signals from its built-in sensors and rear-facing camera. The collected video and inertial data are preprocessed, combined, and then classified by means of a Recurrent Neural Network (RNN) based Sequence-to-Sequence (Seq2Seq) model, which is used as a feature extractor, and a following Convolutional Neural Network (CNN) classifier. This architecture provides excellent results, being able to correctly assess anomalies in 100% of the cases, for the considered tests, surpassing the performance of support vector machine classifiers.