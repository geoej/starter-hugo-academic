---
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hej, jag är EJ!
      username: admin
  - block: features
    content:
      title: Färdigheter
      items:
        - name: Stora språkmodeller
          description: Retrieval-augmented generation, LLM-as-judge, dokumentförståelse, kriterieextraktion
          icon: comments
          icon_pack: fas
        - name: Djupinlärning
          description: PyTorch, TensorFlow, detektionsmodeller, generativa modeller
          icon: brain
          icon_pack: fas
        - name: Biomedicinska signaler
          description: EEG och EKG, oberoende komponentanalys, tidsserieklassificering, kvalitetsmått
          icon: heartbeat
          icon_pack: fas
        - name: Geospatial djupinlärning
          description: SAR- och optiska bilder, Google Earth Engine, detektion och kartläggning
          icon: map
          icon_pack: fas
        - name: Python
          description: NumPy, Pandas, Scikit-learn, PyTorch, TensorFlow
          icon: python
          icon_pack: fab
        - name: MLOps
          description: Docker, Cloud Run, GCP, DVC, MLflow
          icon: cloud-arrow-up
          icon_pack: fas
        - name: Statistik
          description: Inferens, hypotesprövning, modellvalidering, icke-parametriska metoder
          icon: chart-line
          icon_pack: fas
        - name: Databaser
          description: PostgreSQL, MySQL, Neo4j, GraphDB
          icon: database
          icon_pack: fas
  - block: experience
    content:
      title: Erfarenhet
      date_format: Jan 2006
      items:
        - title: FoU-ingenjör / forskare
          company: Chalmers tekniska högskola
          company_url: 'https://www.chalmers.se'
          company_logo:
          location: Göteborg, Sverige
          date_start: '2026-11-01'
          date_end: ''
          description: |2-
              * Maskininlärning för signaler från medicinteknik, med start i HeartBrain: att återskapa hjärtrytm från flerkanaligt EEG när ingen EKG-kanal finns.
              * EKG-fri detektion av hjärtslag med oberoende komponentanalys och ett kvalitetsmått. I undanhållna inspelningar hade de slag som måttet valde median-F1 0,94 och ett fel i hjärtfrekvens på 0,4 slag per minut.
              * Screening av förmaksflimmer från EEG-härledda slag (AUC 0,985 vid typiskt EEG-fel) och hjärtslagsframkallade potentialer hos autistiska barn och barn med typisk utveckling.
              * Preliminära resultat från november 2026. Planerade resultat är en metodartikel, en artikel om förmaksflimmer från sömn-EEG och en öppen Python-verktygslåda.
        - title: Teknisk chef och ledande ingenjör inom geospatial djupinlärning
          company: AquaGuard Technologies AB
          company_url: ''
          company_logo:
          location: Sverige
          date_start: '2026-01-05'
          date_end: '2026-10-01'
          description: |2-
              * Teknisk chef och praktisk AI-ledare för Nexus, en maritim plattform för jordobservation, från TRL 5 mot validerad TRL 6/7.
              * Ledde flersensor-inhämtning och förbehandling av SAR- och optiska bilder, inklusive radiometrisk och geometrisk korrigering och versionshantering av datamängder med DVC och Git.
              * Tränade och validerade detektionsmodeller i PyTorch och TensorFlow, med precision, recall, F1 och förväxlingsmatriser, och testade molndrift.
              * Medledde inferens-API:er (JSON och GeoJSON) och verifiering av WebGIS-panelen som används för att granska detektioner.
        - title: AI-ingenjör (deltid)
          company: Ottomater
          company_url: ''
          company_logo:
          location: ''
          date_start: '2024-07-01'
          date_end: '2026-01-01'
          description: |2-
              * Konstruerade och byggde en evidensbaserad tjänst som rangordnar kandidater utifrån en platsannons och cv:n: https://shortlisting-1016040926675.us-central1.run.app
              * LLM-pipeline för dokumentinläsning, explicita och härledda anställningskriterier, berikning med retrieval och LLM-as-judge med en skriftlig motivering per kriterium.
              * Rangordningen är beslutsstöd för en rekryterare, med kontroller för hallucination, bias och förklarbarhet. Driftsatt på Google Cloud Run.
        - title: Konsult inom datavetenskap (data och AI)
          company: CFF UK
          company_url: www.cropbase.co.uk
          company_log: cfflogo
          location: Cambridge, Storbritannien
          date_start: '2025-04-01'
          date_end: ''
          description: |2-
              * Jag utformar, utvecklar och levererar data- och AI-produkter för EU-projektet RADIANT.
              * Jag använder generativ AI (språkmodeller, diffusionsmodeller och adversariella modeller) för appar och webbplatser på GCP och AWS.
        - title: Chef för datavetenskap
          company: NIAB Ltd
          company_url: ''
          company_logo: niablogo
          location: Cambridge, Storbritannien
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
              * Byggde en databas med mer än 500 europeiska agronomiska studier (1972–2022) och en kunskapsbas för jordbruksdiversifiering på GCP.
              * Levererade AiSQLquery, ett RAG-tillägg för domänfrågor, och en MLOps-pipeline med MLflow och DVC.
        - title: Geospatial datavetare
          company: Crops For the Future (CFF) UK CIC
          company_url: ''
          company_logo: cfflogo
          location: Chelmsford, Storbritannien
          date_start: '2020-05-15'
          date_end: '2023-04-01'
          description: |2-
              * Ledde dataarbetet i Horizon 2020-projektet RADIANT (220 000 euro) och en diversifieringsanalys för Storbritannien över klimat, jord och marknad.
              * Byggde lämplighetsflöden i SQL, Google Earth Engine och GIS, inklusive en nationell 3D-jorddatabas för Sri Lanka.
        - title: Datavetare
          company: Chalmers tekniska högskola (deltid)
          company_url: ''
          company_logo:
          location: Göteborg, Sverige
          date_start: '2021-12-01'
          date_end: '2022-07-01'
          description: |2-
              * Använde spatiala GAN-modeller och annan maskininlärning för att skatta markegenskaper där prover saknades.
              * Uppsats: https://gupea.ub.gu.se/handle/2077/72200?show=full
        - title: Geospatial datavetare
          company: University of Nottingham
          company_url: ''
          company_logo:
          location: Kuala Lumpur, Malaysia
          date_start: '2017-11-01'
          date_end: '2020-05-01'
          description: |2-
              * Ledde 24 specialister som byggde CropBASE-apparna, inom ett Horizon 2020-bidrag på 290 000 euro för ett beslutsstöd om mark.
              * Använde support vector machines för ekonomisk bärkraft och publicerade evidensunderlaget.
        - title: Dataansvarig
          company: University of Nottingham
          company_url: ''
          company_logo:
          location: Kuala Lumpur, Malaysia
          date_start: '2014-08-01'
          date_end: '2017-11-01'
          description: |2-
              * Byggde program som användes av mer än 10 000 jordbrukare i Sydostasien, bland annat ett verktyg för näringstrygghet och en generator för indata till grödmodeller.
        - title: Geospatial ledare
          company: Universiti Putra Malaysia
          company_url: ''
          company_logo:
          location: Kuala Lumpur, Malaysia
          date_start: '2008-09-01'
          date_end: '2014-05-01'
          description: |2-
              * Jämförde rumsliga regressionsmodeller för fastighetsvärdering och byggde PFMap, ett ArcGIS-verktyg för kartor i precisionsodling.
              * Var med och utvecklade hyperspektral analys av oljepalmfrukt, ett arbete som ledde till två patent.
        - title: Geospatial analytiker
          company: Universiti Putra Malaysia (deltid)
          company_url: ''
          company_logo:
          location: Kuala Lumpur, Malaysia
          date_start: '2003-11-01'
          date_end: '2008-08-01'
          description: |2-
              * Stipendium från Malaysian Centre of Remote Sensing. En geostatistisk kartmetod minskade antalet prover med omkring 70 procent.
              * Segmenterade Landsat-bilder och hade ett nationellt bidrag för ett planeringssystem med cellulära automater.
        - title: Datainmatare
          company: National University of Singapore
          company_url: ''
          company_logo:
          location: Singapore
          date_start: '2008-01-01'
          date_end: '2008-08-07'
          description: |2-
              * Byggde ett metadatasystem för fusion av fjärranalysdata i ett marktäckeprojekt i Sydostasien.
              * Transkriberade poster och sökte litteratur om närliggande marktäckestudier.
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Utvalda projekt
      filters:
        folders:
          - project
        tags:
          - Selected
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: false
  - block: markdown
    content:
      title: Galleri
      subtitle: ''
      text: |-
        {{< gallery album="ej" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Utvalda publikationer
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Kontakt
      subtitle:
      text: |-
        Hör av dig, eller boka ett möte:
      email: ej@cropbase.co.uk
      appointment_url: 'https://appt.link/meet-with-ebrahim-jahanshiri-CJwVboa0'
    design:
      columns: '2'
---
