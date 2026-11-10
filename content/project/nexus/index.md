---
title: Nexus
summary: Maritime Earth-observation platform for multi-sensor detection, from data pipelines through validated deep-learning models.
tags:
  - Geospatial Analysis
  - Selected
date: '2026-10-01T00:00:00Z'

external_link: ''

image:
  caption: Illustration
  focal_point: Center

links:
  - icon:
    icon_pack:
    name:
    url:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides:
---

Nexus is the Earth-observation platform I led as CTO at AquaGuard Technologies. The project was first called Trident, and the name was changed to Nexus during the engagement. The work moved the system from a technology readiness level of 5 toward a validated level of 6 to 7.

The data side is a multi-sensor pipeline for SAR and optical imagery. It covers ingestion, radiometric and geometric correction, and versioned training sets tracked with DVC and Git.

The model side is detection trained in PyTorch and TensorFlow. Validation is reported with precision, recall, F1, and confusion matrices, including tests of cloud deployment. Inference is exposed through JSON and GeoJSON APIs, and a WebGIS dashboard is checked so that detections and metadata on screen match the model output.
