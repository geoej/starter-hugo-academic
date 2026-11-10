---
title: Evidence-based LLM shortlisting
summary: A Cloud Run service that ranks candidates from a job description and résumés, with a written justification for every score.
tags:
  - NLP
  - Selected
date: '2026-01-01T00:00:00Z'

external_link: ''

image:
  caption: Illustration
  focal_point: Center

links:
  - icon: globe
    icon_pack: fas
    name: App
    url: https://shortlisting-1016040926675.us-central1.run.app
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

slides:
---

Built for Ottomater, this service turns a job description and a set of résumés into a ranked shortlist. A large language model extracts explicit requirements and a small set of inferred criteria, enriches them with retrieval, and scores each candidate against each criterion.

Every score comes with a short justification and a longer explanation. The ranking is decision support for a recruiter, not an automated hiring decision. The design includes checks for hallucinated qualifications, biased assessments, and explanations that cannot be audited.

The app is deployed on Google Cloud Run: https://shortlisting-1016040926675.us-central1.run.app
