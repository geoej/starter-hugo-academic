---
title: Nexus
summary: Maritim plattform för jordobservation, från flersensor-pipelines till validerade djupinlärningsmodeller.
tags:
  - Geospatial analys
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

Nexus är den plattform för jordobservation som jag ledde som teknisk chef på AquaGuard Technologies. Projektet hette först Trident och bytte namn till Nexus under uppdraget. Arbetet flyttade systemet från teknisk mognadsgrad 5 mot en validerad nivå 6 till 7.

Datasidan är en flersensor-pipeline för SAR- och optiska bilder. Den omfattar inhämtning, radiometrisk och geometrisk korrigering och versionshanterade träningsmängder med DVC och Git.

Modelsidan är detektion tränad i PyTorch och TensorFlow. Valideringen redovisas med precision, recall, F1 och förväxlingsmatriser, inklusive tester av molndrift. Inferens exponeras via JSON- och GeoJSON-API:er, och en WebGIS-panel kontrolleras så att detektioner och metadata på skärmen stämmer med modellens utdata.
