---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      username: admin
    
  - block: features
    id: skills
    content:
      title: Laboratory Skills
      items:
        - name: Analytical Chemistry Methods
          icon: flask-vial
          icon_package: fab
          description: HPLC-MS, CE, SPE, Glycoscience
        - name: DNA Manipulation
          icon: dna
          icon_package: fab
          description: Mutagenesis, Cloning Techniques, Sequence Analysis
        - name: Molecular Biology
          icon: vial-virus
          icon_package: fab
          description: PCR, RFLP, ELISA, STR, VNTR
    
  - block: features
    content:
      title: Computational Skills
      items:
        - name: R
          icon: r-project
          icon_pack: fab
          description: Biostatistics & Data Visualization
        - name: Python
          icon: python
          icon_pack: fab
          description: Data Manipulation & Analysis
        - name: Excel
          icon: file-excel
          icon_package: fab
          description: Multiple Applications
    
  - block: experience
    id: experience
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
        - title: Laboratory Technician
          company: SGS
          company_url: ''
          company_logo: org-sgs
          location: Burnaby
          date_start: '2023-07-01'
          date_end: ''
          description: Part of the Digestion Laboratory in the Geochemistry Department.
        - title: Research Assistant
          company: The University of British Columbia
          company_url: ''
          company_logo: org-ubc
          location: Kelowna
          date_start: '2022-05-01'
          date_end: '2023-04-01'
          description: Led the dairy department team and conducted research projects aiming at the characterization of milk oligosaccharides.
        - title: Laboratory Assistant
          company: Zandberg Laboratory
          company_url: ''
          company_logo: org-zendy
          location: Kelowna
          date_start: '2021-01-01'
          date_end: '2022-04-01'
          description: Collaborated with numerous researchers to elucidate milk's glycobiology to improve infant nutrition.
        - title: Organic Chemistry & Biostatistics Teacher Assistant
          company: The University of British Columbia
          company_url: ''
          company_logo: org-ubc
          location: Kelowna
          date_start: '2021-09-01'
          date_end: '2023-04-01'
          description: Worked with the Department of Biology and Chemistry to support UBCO students’ learning and achievements.
    
      design:
        columns: '2'
    
  - block: accomplishments
    id: accomplishments
    content:
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
        - date_end: ''
          date_start: '2023-04-01'
          description: Requires a high academic standing and preparation of a graduating thesis.
          organization: UBC
          organization_url: https://www.ubc.ca/
          title: Honours 
        - certificate_url: uploads/IURA.pdf
          date_end: ''
          date_start: '2022-04-01'
          description: '$10,500 granted to students to pursue innovative and original research.'
          organization: UBC
          organization_url: https://www.ubc.ca/
          title: International Undergraduate Research Award
        - certificate_url: uploads/banff.pdf
          date_end: ''
          date_start: '2022-05-01'
          description: A national platform supports translational research, protection of intellectual property, novel drug development, company formation and training of a new generation of glyco-scientists and entrepreneurs.
          organization: GlycoNet
          organization_url: https://canadianglycomics.ca/
          title: Canadian Glycomics Symposium (Banff 2022)
        - date_end: ''
          date_start: '2022-11-01'
          description: Convenes worldwide scientists that investigate animal science.
          organization: ULPGC
          organization_url: https://www.ulpgc.es/
          title: International Scientific Meeting on Colostrum (Spain 2022)
        - date_end: ''
          date_start: '2023-04-01'
          description: Recognizes students who have demonstrated academic excellence by maintaining a sessional average of at least 85% while completing 24 or more credits.
          organization: UBC
          organization_url: https://www.ubc.ca/
          title: Dean's List

    design:
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
        - name: Data Analytics
          tag: Git 
        - name: Academic
          tag: Acad
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  # block: collection
   # id: blog
   # content:
     # title: Blog
     # subtitle: ''
     # text: ''
      # Choose how many pages you would like to display (0 = all pages)
     # count: 5
      # Filter on criteria
     # filters:
       # folders:
         # - post
       # author: ""
       # category: ""
       # tag: ""
       # exclude_featured: false
       # exclude_future: false
       # exclude_past: false
       # publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
     # order: desc
   # design:
      # Choose a layout view
     # view: compact
     # columns: '2'
    
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Let's connect!
      # Contact (add or remove contact options as necessary)
      email: cltomiyama@gmail.com
      phone: 250 575 4732
      appointment_url: 'https://calendly.com/carolinatomiyama'
      address:
        city: Vancouver
        region: BC
        country: Canada
        country_code: CA
    
    
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
     
    design:
      columns: '2'
---
