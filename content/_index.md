---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    id: features
    content:
      title: Skills
      items:
        - name: Programming Language
          description: |
              Python (Obspy, Scipy, Basemap)
          icon: python
          icon_pack: fab
        - name: Geophysical Software
          description: |2-
              Geopsy\
              Dinver\
              PySeismoSoil\
              DEEPSOIL
          icon: computer
          icon_pack: fas
        - name: Geophysical Exploration
          description: |
              Surface Wave Inversion
          icon: magnifying-glass
          icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Conferences
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Site effect assessment of the Nakdonggang delta sediments using a depth-dependent shear wave velocity model, Oral
          company: Earthquake Engineering Society of Korea 2023 Workshop
          company_url: ''
          company_logo: ''
          location: Jeju-do, Korea
          date_start: '2023-09-13'
          date_end: '2023-09-13'
          description: Jaehwi Kim, Junsu Oh and seokho Jeong
             
    
        - title: Site effect assessment of the Late-Quaternary sediments in the Nakdonggang delta region using HVSR and MAM techniques, Oral
          company: Busan/Ulsan/Gyeongnam Branch Convention of Korean Society of Civil Engineers
          company_url: ''
          company_logo: ''
          location: Busan, Korea 
          date_start: '2023-09-01'
          date_end: '2023-09-01'
          description: Jaehwi Kim and Seokho Jeong
    
        - title: Prediction of ground motion in South Korea based on hybrid broadband ground motion simulation
          company: IUGG(International Union of Geodesy and Geophysics)
          company_url: ''
          company_logo: ''
          location: Berlin, Germany
          date_start: '2023-07-13'
          date_end: '2023-07-13'
          description: S.Jeong, S.E. Bae, J.H. Kim and B.A. Bradley
    
        - title: A shear wave velocity model of Gimhae Plains sediments based on the Microtremor Array Method, Oral
          company: KSCE Convention
          company_url: ''
          company_logo: ''
          location: Busan, Korea
          date_start: '2022-10-18'
          date_end: '2022-10-18'
          description: Jaehwi Kim and Seokho Jeong
    
        - title: Prediction of ground motion in South Korea based on physics-based broadband simulation
          company: SCEC Annual Meeting
          company_url: ''
          company_logo: ''
          location: Palm Springs, United States
          date_start: '2022-09-11'
          date_end: '2022-09-11'
          description: Seokho Jeong, Sung Bae, JaeHwi Kim and Kwangyoung Kim
    
        - title: Broadband Physics-based strong ground motion simulations for the southern Korean Peninsula
          company: QuakeCoRE Annual Meeting
          company_url: ''
          company_logo: ''
          location: Napier, New Zealand
          date_start: '2022-08-30'
          date_end: '2022-08-30'
          description: S.Bae, S.Jeong, J.Kim and K.Kim
    
        - title: Characterization of dynamic site properties in the Gimhae Plains using the Microtremor Array Method and the Horizontal-to-Vertical Spectral Ratio method, Poster
          company: QuakeCoRE Annual Meeting
          company_url: ''
          company_logo: ''
          location: Napier, New Zealand
          date_start: '2022-08-30'
          date_end: '2022-08-30'
          description: Jaehwi Kim and Seokho Jeong
    
        - title: Characterization of shear wave velocity in the Gimhae Plains using the Microtremor Array Method
          company: KGS Spring National Conference
          company_url: ''
          company_logo: ''
          location: Seoul, Korea
          date_start: '2022-03-16'
          date_end: '2022-03-16'
          description:  Seokho Jeong and Jaehwi Kim
    
        - title: Estimation of velocity structures in the Gimhae Plains using horizontal-to-vertical spectral ratios from microtremors, Oral
          company: KGS Fall National Conference
          company_url: ''
          company_logo: ''
          location: Seoul, Korea
          date_start: '2021-10-01'
          date_end: '2021-10-01'
          description: Jaehwi Kim and Seokho Jeong  
    design:
      columns: '2'

    
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Publications'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://doi.org/10.3390/geotechnics3030030
          date_end: ''
          date_start: '2023-06-21'
          description: Kim, J. Heo, G. Kwak, D. Jeong, S
          organization: Geotechnics
          organization_url:  
          title: The Relationship between Bedrock Depth and Site Fundamental Frequency in the Nakdonggang Delta Region,South Korea
          url: ''
    
        - certificate_url: https://doi.org/10.7843/kgs.2022.38.8.17
          date_end: ''
          date_start: '2023-02-01'
          description: Jaehwi Kim
          organization: Master's Thesis
          organization_url:  
          title: Characterization of dynamic site properties in the Gimhae Plains using the Microtremor Array Method and the Horizontal-to-Vertical Spectral Ratio method
          url: 
    
        - certificate_url: https://doi.org/10.7843/kgs.2022.38.8.17
          date_end: 
          date_start: '2022-08-31'
          description: 'Jaehwi Kim and Seokho Jeong'
          organization: Journal of the Korean Geotechnical Society
          organization_url: 
          title: 'Characterization of Deep Shear Wave Velocity Profiles in the Gimhae Plains Using the Microtremor Array Method'
          url: ''
    design:
      columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:        
      # Contact (add or remove contact options as necessary)
      email: 20143041@changwon.ac.kr
      address:
        
        city: Changwon
        region: Gyeongsangnam-do
        postcode: '51149'
        country: South Korea
        
      
    design:
      columns: '2'
---
