---
title: Evidensbaserad kortlistning med språkmodell
summary: En tjänst på Cloud Run som rangordnar kandidater utifrån en platsannons och cv:n, med en skriftlig motivering för varje poäng.
tags:
  - Språkteknologi
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

Tjänsten, byggd för Ottomater, gör om en platsannons och en uppsättning cv:n till en rangordnad kortlista. En stor språkmodell plockar ut uttalade krav och en liten mängd härledda kriterier, berikar dem med retrieval och poängsätter varje kandidat mot varje kriterium.

Varje poäng har en kort motivering och en längre förklaring. Rangordningen är beslutsstöd för en rekryterare, inte ett automatiskt anställningsbeslut. Konstruktionen innehåller kontroller för påhittade meriter, snedvridna bedömningar och förklaringar som inte går att granska.

Appen körs på Google Cloud Run: https://shortlisting-1016040926675.us-central1.run.app
