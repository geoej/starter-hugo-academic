---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hi, I'm EJ!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Large language models
          description: Retrieval-augmented generation, LLM-as-judge scoring, document understanding, criteria extraction
          icon: comments
          icon_pack: fas
        - name: Deep learning
          description: PyTorch, TensorFlow, detection models, generative models
          icon: brain
          icon_pack: fas
        - name: Biomedical signal ML
          description: EEG and ECG, independent component analysis, time-series classification, quality scoring
          icon: heartbeat
          icon_pack: fas
        - name: Geospatial deep learning
          description: SAR and optical imagery, Google Earth Engine, detection and mapping
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
        - name: Statistics
          description: Inference, hypothesis testing, model validation, non-parametric methods
          icon: chart-line
          icon_pack: fas
        - name: Databases
          description: PostgreSQL, MySQL, Neo4j, GraphDB
          icon: database
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: R&D Engineer / Scientist
          company: Chalmers University of Technology
          company_url: 'https://www.chalmers.se'
          company_logo:
          location: Gothenburg, Sweden
          date_start: '2026-11-01'
          date_end: ''
          description: |2-
              * Machine learning for medical-device signals, starting with HeartBrain: recovering heart rhythm from multichannel EEG when no ECG channel is available.
              * ECG-free heartbeat detection with independent component analysis and a quality score. On held-out recordings the score selected beats with median F1 0.94 and heart-rate error of 0.4 bpm.
              * Atrial-fibrillation screening from EEG-derived beats (AUC 0.985 under typical EEG error) and heartbeat-evoked potentials in autistic and typically developing children.
              * Preliminary results from November 2026. Planned outputs are a methods paper, an atrial-fibrillation-from-sleep-EEG paper, and an open-source Python toolbox.
        - title: CTO and Lead Geospatial Deep Learning Engineer
          company: AquaGuard Technologies AB
          company_url: ''
          company_logo:
          location: Sweden
          date_start: '2026-01-05'
          date_end: '2026-10-01'
          description: |2-
              * Chief technology officer and hands-on AI lead for Nexus, a maritime Earth-observation platform, taking the system from TRL 5 toward validated TRL 6/7.
              * Led multi-sensor ingestion and preprocessing for SAR and optical imagery, including radiometric and geometric correction and dataset versioning with DVC and Git.
              * Trained and validated detection models in PyTorch and TensorFlow, reporting precision, recall, F1, and confusion matrices, and tested cloud deployment.
              * Co-led inference APIs (JSON and GeoJSON) and verification of the WebGIS dashboard used to review detections.
        - title: AI Engineer (part time)
          company: Ottomater
          company_url: ''
          company_logo:
          location: ''
          date_start: '2024-07-01'
          date_end: '2026-01-01'
          description: |2-
              * Designed and built an evidence-based candidate shortlisting service that ranks applicants from a job description and résumés: https://shortlisting-1016040926675.us-central1.run.app
              * LLM pipeline for document ingestion, explicit and inferred hiring criteria, retrieval-augmented enrichment, and LLM-as-judge scoring with a written justification per criterion.
              * Rankings are decision support for a recruiter, with checks for hallucination, bias, and explainability. Deployed on Google Cloud Run.
        - title: Consultant Data Scientist (Data & AI)
          company: CFF UK
          company_url: www.cropbase.co.uk
          company_log: cfflogo
          location: Cambridge, UK 
          date_start: '2025-04-01'
          date_end: ''
          description: |2-
              * I design, develop, and deliver data and AI products for the EU RADIANT project.
              * I use Generative AI (LLMs, Diffusion and Adversarial models) to develop apps and website deployed on GCP, AWS. 
        - title: Data Science Manager
          company: NIAB Ltd
          company_url: ''
          company_logo: niablogo
          location: Cambridge, UK
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
              * Built a database of more than 500 European agronomic studies (1972–2022) and a knowledge base for agricultural diversification on GCP.
              * Shipped AiSQLquery, a retrieval-augmented extension for domain questions, and an MLOps pipeline with MLflow and DVC.
        - title: Geospatial Data Scientist 
          company: Crops For the Future (CFF) UK CIC
          company_url: ''
          company_logo: cfflogo
          location: Chelmsford, UK
          date_start: '2020-05-15'
          date_end: '2023-04-01'
          description: |2-
              * Led the data work for the RADIANT Horizon 2020 project (220,000 euro) and a UK diversification analysis across climate, soil, and markets.
              * Built suitability workflows on SQL, Google Earth Engine, and GIS, including a national 3D soil database for Sri Lanka.
        - title: Data Scientist
          company: Chalmers University of Technology (part time)
          company_url: ''
          company_logo: 
          location: Gothenburg, Sweden
          date_start: '2021-12-01'
          date_end: '2022-07-01'
          description: |2-
              * Used spatial GANs and other models to estimate soil properties where samples were missing.
              * Thesis: https://gupea.ub.gu.se/handle/2077/72200?show=full
        - title: Geospatial Data Scientist 
          company: University of Nottingham
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2017-11-01'
          date_end: '2020-05-01'
          description: |2-
              * Led 24 specialists building the CropBASE apps, under a 290,000 euro Horizon 2020 grant for a land decision-support system.
              * Applied support vector machines to economic feasibility and published the evidence base.
        - title: Data Manager 
          company: University of Nottingham
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2014-08-01'
          date_end: '2017-11-01'
          description: |2-
              * Built software used by more than 10,000 farmers in Southeast Asia, including a nutrition-security tool and a crop-model input generator.
        - title: Geospatial Lead 
          company: Universiti Putra Malaysia
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2008-09-01'
          date_end: '2014-05-01'
          description: |2-
              * Compared spatial regression models for property valuation and built PFMap, an ArcGIS tool for precision-farming maps.
              * Co-developed hyperspectral analysis of oil-palm fruit that led to two patents.
        - title: Geospatial Analyst
          company: Universiti Putra Malaysia (part time)
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2003-11-01'
          date_end: '2008-08-01'
          description: |2-
              * Fellowship from the Malaysian Centre of Remote Sensing. A geostatistical mapping method cut the samples needed by about 70 percent.
              * Segmented Landsat imagery and held a national grant for a cellular-automata planning system.
        - title: Data Entry Specialist
          company: National University of Singapore
          company_url: ''
          company_logo: 
          location: Singapore
          date_start: '2008-01-01'
          date_end: '2008-08-07'
          description: |2-
              * Built a metadata system for remote-sensing data fusion in a Southeast Asia land-cover project.
              * Transcribed records and searched the literature for related land-cover studies.                
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://credentials.databricks.com/b21fa851-4249-40be-a0c5-3dd804152d1c#main-content
  #         date_end: ''
  #         date_start: '2023-11-05'
  #         description: 'Academy Accreditation - '
  #         organization: Databricks
  #         organization_url: https://www.databricks.com
  #         title: Databricks Lakehouse Fundamentals
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Selected projects
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
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="ej" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Drop a line to connect or alternatively schedule a meeting:
      # Contact (add or remove contact options as necessary)
      email: ej@cropbase.co.uk
      #phone: 888 888 88 88
      appointment_url: 'https://appt.link/meet-with-ebrahim-jahanshiri-CJwVboa0'
      #address:
      #  street: Huntingdon Road
      #  city: Cambridge
      #  region: CA
      #  postcode: '94305'
      #  country: United Kingdom
      #  country_code: UK
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      #autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---

