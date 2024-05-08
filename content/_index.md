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
        - name: Statistics
          description: 3D and 2D data analysis, Inferences, Hypothesis Testing, Non-parametric Statistics
          icon: chart-line
          icon_pack: fas
        - name: Machine Learning
          description: Generative Adversarial Neural Networks, Random Forest
          icon: brain
          icon_pack: fas
        - name: Geospatial mapping
          description: ArcGIS, QGIS, Google Earth Engine
          icon: map
          icon_pack: fas
        - name: Management 
          description: Budgeting, Publishing, Reporting, Grant Writing, CI/CD
          icon: list-check
          icon_pack: fas
        - name: R
          description: Tidyverse, sf, terra, ggplot, shiny
          icon: r-project
          icon_pack: fab
        - name: Python
          description: NumPy, Pandas, Scikit-learn, PyTorch, TensorFlow
          icon: python
          icon_pack: fab
        - name: Database
          description: PostgreSQL, MySQL, Neo4j, GraphDB
          icon: database
          icon_pack: fas
        - name: Cloud Computing & DevOps
          description: GCP (Compute Engine, Cloud APIs), Docker, VM, Apache
          icon: cloud-arrow-up
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
        - title: Data Science Manager
          company: NIAB Ltd
          company_url: ''
          company_logo: niablogo
          location: Cambridge, UK
          date_start: '2023-04-01'
          date_end: ''
          description: |2-    
              * Developed a database for more than 500 agronomic studies that were published across European agroclimatic zones from 1972 to 2022: https://zenodo.org/records/8406516
              * Developed a crop model to assess the potential of Proso millet as a climate-resilient crop for sustainable diversification. https://zenodo.org/records/7456224
              * Developed a Global knowledge base for agricultural diversification with MYSQL, PHP on Google Cloud Platform (GCP): https://github.com/geoej/RADIANT-DB
              * AiSQLQury: an Retrieval Augmented Generation (RAG) based Large Language Model (LLM) extension for domain specific data augmentation: https://github.com/geoej/AiSQLquery
              * MlOps: end-to-end model production with MLflow and DVC deployment: https://github.com/geoej/EndtoEndDVC
        - title: Geospatial Data Scientist 
          company: Crops For the Future (CFF) UK CIC
          company_url: ''
          company_logo: cfflogo
          location: Chelmsford, UK
          date_start: '2020-05-15'
          date_end: '2023-04-01'
          description: |2-
              * Awarded “Realising Dynamic Value Chains for Underutilised Crops (RADIANT) - HORIZON 2020 SFS-01-2020”. H2020 European Union. Granted 220,000 Euros. https://www.radiantproject.eu
              * Developed a multistage suitability assessment based on available data at local, regional and global level (SQL database, Google Earth Engine, local meteorological and prices datasets) to provide initial evidence for the economic feasibility of hemp: https://www.sciencedirect.com/science/article/abs/pii/S0926669021007640
              * Developed an analysis framework for diversification in the United Kingdom, considering climate, soil, economics, and market demand. API database of 2700 crops, combined GIS and data mining to determine the most promising climate resilitent crop for the UK: https://www.mdpi.com/2077-0472/13/4/787
              * Developed a data-driven approach for shortlisting underutilized crops (UCs) for sustainable agricultural diversification across Italy: https://www.mdpi.com/2073-4395/12/7/1636 
              * Quantified the fitness of global datasets for forest Loss quantification in Amazonia based on R and Google Earth Engine: https://github.com/geoej/ForestLossDatasets/
              * Carried out spatial suitability analysis of bambara groundnut in China using stochastic environmental research and risk assessment, sub-daily swat models, cluster analysis, economic data, climate data, soil data, crop production data, and FAOSTAT data: https://onlinelibrary.wiley.com/doi/full/10.1002/fes3.358
              * Lead the development of The first version of nation-wide open 3D soil database for Sri Lanka: https://www.sciencedirect.com/science/article/pii/S235234092031235X
        - title: Data Scientist
          company: Chalmers University of Technology (part time)
          company_url: ''
          company_logo: 
          location: Gothenburg, Sweden
          date_start: '2021-12-01'
          date_end: '2022-07-01'
          description: |2-
              * Utilised the Spatial Generative Adversarial Neural Networks (SpaceGAN) and machine learning models to predict soil properties at unsampled areas (due to high cost). The results show that this method can improve the accuracy of soil information.
              * Spatial Generative Adversarial Networks (SpaceGANs)
              * Data mining from published resources
              * Machine learning models Read more: https://gupea.ub.gu.se/handle/2077/72200?show=full
        - title: Geospatial Data Scientist 
          company: University of Nottingham
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2017-11-01'
          date_end: '2020-05-01'
          description: |2-
              * Awarded EUR 290,000 for the project: “Development of Integrated Web-Based Land Decision Support System Aiming Towards the Implementation of Policies for Agriculture and Environment”. (H2020-RUR-2017-2). https://www.landsupport.eu
              * Lead a team of 24 data specialists, and software developers to develop CropBASE suite of Apps for agricultural diversification: https://www.cropbase.co.uk 
              * Crop suitability mapper https://www.cropbase.co.uk/src/cropgrids/cropgrids.php
              * AssessCrop: the first evidence-base for new products and their nutrition from underutilised crops: https://cropbase.co.uk/src/assesscrop/assesscrop/product_compare.php
              * Developed a Global Knowledge Base for agricultural diversification: https://cropbase.co.uk/cropbasev5/
              * Utilised Support Vector Machines algorithm for the economic feasibility assessment of underutilised crops: https://www.sciencedirect.com/science/article/abs/pii/S0168169918306665
        - title: Data Manager 
          company: University of Nottingham
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2014-08-01'
          date_end: '2017-11-01'
          description: |2-
              * Developed a suite of software and tools for diversification of agriculture for more than 10,000 farmers in South East Asia.
              * A Nutrition Security Tool demonstrating the importance of Underutilised Food Crops for Sustainable Nutrition Security https://geoprocessing.shinyapps.io/underutilised/
              * DSSAT-INPUT: an online DSSAT-compatible crop modelling input generator https://geoprocessing.shinyapps.io/DSSAT-INPUT-Shiny/
              * Developed Data frameworks for linking data across different disciplines: https://www.myfoodresearch.com/uploads/8/4/8/5/84855864/_4__fr-2018-104.r1_nur_marahaini.pdf
        - title: Geospatial Lead 
          company: Universiti Putra Malaysia
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2008-09-01'
          date_end: '2014-05-01'
          description: |2-
              * Graduate research fellowship funded the Government of Malaysia, Ministry of Higher Education
              * Developed R code to compare specifications of linear regression and spatial-temporal autoregressive models in mass appraisal valuation for single storey residential property: http://psasir.upm.edu.my/id/eprint/60054
              * Developed a spatial regression techniques for prediction of house property values.
              * Developed PFMap macro creates continuous availability and application maps for precision farming. A stand-alone ArcGIS macro developed with ArcObjects and VBA.
              * Participated in the development of Hyperspectral analysis of oil palm fruit project that to 2 patents.
              * Developed a comprehensive review of spatial analysis of Property sales. The published paper has received more than 100 citation: https://core.ac.uk/download/pdf/153802057.pdf
              * Developed Shiny PFMap software, soil mapper using R statistical libraries https://geoprocessing.shinyapps.io/geoprocessing/  data for testing the App: http://b.link/a69
              * Developed An Automated Valuation System for real estate appraisal based on geospatial regression techniques. A standalone software based on R programming language and TCL/TK
        - title: Geospatial Analyst
          company: Universiti Putra Malaysia (part time)
          company_url: ''
          company_logo: 
          location: Kuala Lumpur, Malaysia
          date_start: '2003-11-01'
          date_end: '2008-08-01'
          description: |2-
              * Graduate research fellowship funded by The Malaysian Centre of Remote Sensing (MACRES)
              * Developed a complete algorithm for geostatistical analysis and mapping that would reduce the number of samples required for mapping by 70%: https://link.springer.com/article/10.1007/s12517-015-1912-6
              * Developed object-oriented approach for image segmentation using LandSat data (UGSS)
              * Granted RM 135,000 (Ringgit Malaysia). “Developing a cellular automata-based planning decision support system” (01-01-04-SF0979), Ministry of Science, Technology and Innovation
        - title: Data Entry Specialist
          company: National University of Singapore
          company_url: ''
          company_logo: 
          location: Singapore
          date_start: '2008-01-01'
          date_end: '2008-08-07'
          description: |2-
              * Developed a metadata system for remote sensing data fusion for "Land-use Land-cover Change and Its Environmental Consequences in Southeast Asia" project
              * Transcribed records for the project: "Effects of clearance and fragmentation on forest compositional change and recovery after 200 years in western New York"
              * Conducted literature search for the project "land-use land-cover change research explored using self-organizing map"                
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://credentials.databricks.com/b21fa851-4249-40be-a0c5-3dd804152d1c#main-content
          date_end: ''
          date_start: '2023-11-05'
          description: 'Academy Accreditation - '
          organization: Databricks
          organization_url: https://www.databricks.com
          title: Databricks Lakehouse Fundamentals
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
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
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
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
      appointment_url: 'https://calendly.com/jgeo067/30min'
      address:
        street: Huntingdon Road
        city: Cambridge
        #region: CA
        #postcode: '94305'
        country: United Kingdom
        country_code: UK
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

