---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: 
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 5 years of experience with common data mining and machine learning tools
          icon: python
          icon_pack: fab
        - name: Machine Learning
          description: Experience with common packages including Scikit-learn, TensorFlow, PyTorch, Optuna, MLflow
          icon: brain
          icon_pack: fas
        - name: Natural Language Processing
          description: Research experience with transformer-based architectures such as BERT, as well as common packages including NLTK, SpaCy, TextBlob
          icon: file-lines
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
        - title: Research Assistant
          company: Fraunhofer Institute for Algorithms and Scientific Computing
          company_url: 'https://www.scai.fraunhofer.de/'
          company_logo: org-gc
          location: Sankt Augustin, Germany
          date_start: '2021-05-01'
          date_end: '2022-08-01'
          description: |3-
                AIOLOS Project (Artificial Intelligence Tools for Outbreak Detection and Response)

                The goal of the project is to develop a digital platform to allow for early detection of new respiratory pathogens epidemics, monitor their spread, and inform decision-makers on appropriate countermeasures. 

                My task was to perform opinion mining on German tweets to monitor public perception of measures taken by the government in the context of COVID-19 nonpharmaceutical interventions (NPIs).

        - title: Master Thesis Student
          company: Fraunhofer Institute for Algorithms and Scientific Computing
          company_url: 'https://www.scai.fraunhofer.de/'
          company_logo: org-gc
          location: Sankt Augustin, Germany
          date_start: '2021-07-01'
          date_end: '2022-05-01'
          description: |
                Thesis Title : Disease-Symptom Relation Extraction from Biomedical Textual Content
                
                The main purpose of this research was to extract relations between diseases and their corresponding symptoms from PubMed abstracts. To achieve this, we created a novel dataset by using various active learning (AL) methods which is a form of semi-supervised learning. After the construction of the dataset, we fine-tuned BERT based models which are pre-trained on the biomedical text. 
    
        - title: Research Intern
          company: Bayer AG
          company_url: 'https://www.bayer.com/en/'
          company_logo: org-x
          location: Leverkusen, Germany
          date_start: '2020-10-15'
          date_end: '2021-04-15'
          description: |
              Biotechnology with Focus on Laboratory Automation 
              
              * Programmed a pipetting robot to implement enzyme activity assay experiments
              * Setted up half-throughput fluorescence assays for enzyme activity screening
              * Implemented a Python-based data analysis and visualization pipeline
    
    design:
      columns: '2'
  #- block: accomplishments
    #content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      #title: 'Accomplish&shy;ments'
      #subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      #date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      #items:
      #  - certificate_url: https://www.coursera.org
      #    date_end: ''
      #    date_start: '2021-01-25'
      #    description: ''
      #    organization: Coursera
      #    organization_url: https://www.coursera.org
      #    title: Neural Networks and Deep Learning
      #    url: ''
      #  - certificate_url: https://www.edx.org
      #    date_end: ''
      #    date_start: '2021-01-01'
      #    description: Formulated informed blockchain models, hypotheses, and use cases.
      #    organization: edX
          #organization_url: https://www.edx.org
          #title: Blockchain Fundamentals
          #url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        #- certificate_url: https://www.datacamp.com
          #date_end: '2020-12-21'
          #date_start: '2020-07-01'
          #description: ''
          #organization: DataCamp
          #organization_url: https://www.datacamp.com
          #title: 'Object-Oriented Programming in R'
          #url: ''
    #design:
      #columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Blog Posts
  #    subtitle: ''
  #    text: ''
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
      # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
   #     folders:
   #       - publication
   #     exclude_featured: true
   # design:
   #   columns: '2'
   #   view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  
  #- event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        If you want to reach out to me, you can use the form below.
      # Contact (add or remove contact options as necessary)
      #email: test@example.org
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        #street: 450 Serra Mall
        city: Düsseldorf
        region: Germany
        #postcode: '40215'
        country: Germany
        country_code: DE
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/uzaygokay'
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
        #- icon: video
        #  icon_pack: fas
        #  name: Zoom Me
        #  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
