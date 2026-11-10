---
title: HeartBrain
summary: ECG-free heart-rhythm recovery from multichannel EEG, for atrial-fibrillation screening and heart–brain measures.
tags:
  - Data Science
  - Selected
date: '2026-11-01T00:00:00Z'

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

HeartBrain is research at Chalmers on reading the heart from the EEG. Clinical and wearable EEG often has no ECG channel, so the cardiac signal is discarded as artifact. This project recovers the heartbeat from the EEG itself, then asks when that rhythm is reliable enough to use.

Independent component analysis separates the heartbeat from the brain signal. A quality score, computed without an ECG, selects the recordings where the recovered beats can be trusted. On held-out adult and paediatric recordings, recordings flagged by that score had a median F1 of 0.94 against chest ECG and a heart-rate error of 0.4 bpm.

Two applications follow from the same beats. One is atrial-fibrillation screening from routine sleep EEG: a classifier trained on long ECG records kept an AUC of 0.985 after realistic EEG beat errors were added. The other is the heartbeat-evoked potential in autistic and typically developing children, which normally requires an ECG the recordings do not have.

These are preliminary results from November 2026. They will be re-run independently before any paper. Planned outputs are a methods paper, an atrial-fibrillation paper, and an open-source Python toolbox.
