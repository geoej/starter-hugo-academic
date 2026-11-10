---
title: HeartBrain
summary: EKG-fri återhämtning av hjärtrytm från flerkanaligt EEG, för screening av förmaksflimmer och mått på hjärta–hjärna.
tags:
  - Datavetenskap
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

HeartBrain är forskning på Chalmers om att läsa hjärtat ur EEG. Kliniskt EEG och bärbart EEG saknar ofta en EKG-kanal, och hjärtsignalen kastas då bort som artefakt. Projektet återskapar hjärtslagen ur själva EEG-signalen och frågar när den rytmen är tillräckligt tillförlitlig för att användas.

Oberoende komponentanalys skiljer hjärtslagen från hjärnsignalen. Ett kvalitetsmått, beräknat utan EKG, väljer de inspelningar där de återskapade slagen går att lita på. I undanhållna inspelningar från vuxna och barn hade de inspelningar som måttet flaggade en median-F1 på 0,94 mot bröst-EKG och ett fel i hjärtfrekvens på 0,4 slag per minut.

Samma slag ger två tillämpningar. Den ena är screening av förmaksflimmer från vanligt sömn-EEG: en klassificerare tränad på långa EKG-inspelningar behöll AUC 0,985 efter att realistiska EEG-fel lagts på. Den andra är den hjärtslagsframkallade potentialen hos autistiska barn och barn med typisk utveckling, ett mått som annars kräver ett EKG som inspelningarna inte har.

Det här är preliminära resultat från november 2026. De ska köras om av någon annan innan någon artikel skrivs. Planerade resultat är en metodartikel, en artikel om förmaksflimmer och en öppen Python-verktygslåda.
