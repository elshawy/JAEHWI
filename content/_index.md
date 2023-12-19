---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title : Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - date_end: ''
          date_start: '2023-10-01'
          description: 'Heo, G. Kim, J. Jeong, S. Kwak, D (doi : https://doi.org/10.3390/geotechnics3040054)'
          organization: Geotechnics
          organization_url:  
          title: Evaluation of Shear Wave Velocity Prediction Models from Standard Penetration Test N Values Depending on Geologic Attributes, A Case Study in Busan, South Korea
          url: ''
    
        - date_end: ''
          date_start: '2023-06-21'
          description: 'Kim, J. Heo, G. Kwak, D. Jeong, S (doi : https://doi.org/10.3390/geotechnics3030030)'
          organization: Geotechnics
          organization_url:  
          title: The Relationship between Bedrock Depth and Site Fundamental Frequency in the Nakdonggang Delta Region,South Korea
          url: ''
    
        - date_end: ''
          date_start: '2023-02-01'
          description: 'Jaehwi Kim (doi : https://doi.org/10.7843/kgs.2022.38.8.17)'
          organization: Master's Thesis
          organization_url:  
          title: Characterization of dynamic site properties in the Gimhae Plains using the Microtremor Array Method and the Horizontal-to-Vertical Spectral Ratio method
          url: 
    
        - date_end: 
          date_start: '2022-08-31'
          description: 'Jaehwi Kim and Seokho Jeong (doi : https://doi.org/10.7843/kgs.2022.38.8.17)'
          organization: Journal of the Korean Geotechnical Society
          organization_url: 
          title: 'Characterization of Deep Shear Wave Velocity Profiles in the Gimhae Plains Using the Microtremor Array Method'
          url: ''
    design:
      columns: '2'
    
  - block: experience
    id: Projects
    content:
      title: Projects
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Amplification Correction of Seismic Records for Real Time Estimates of the Seismic Intensity
          company: 'R&D Management Agency : Korea Meteorological Institute, Student Researcher'
          date_start: '2023-03-01'
          date_end: ''
          description: |2
                        - Review of Current Alert and Forecasting Criteria in Korea and Abroad
                        - Investigation of the Operation Patterns and Characteristics of the Seismic Observation Stations
                        - Comparison of Real-Time Seismic Information Processing Algorithms
    
        - title: Determining Design Ground Motion for the Nakdonggang Delta Region Using Broadband Hybrid Ground Motion Simulation
          company: 'R&D Management Agency : Changwon National University, Principal Investigator'
          date_start: '2023-03-01'
          date_end: ''
          description: |2
                       - Collection of Data Related to Current Seismic Design Standards in South Korea and Abroad
                       - Broadband Hybrid Ground Motion Simulation (Virtual Earthquake Scenario Setup and Execution)
                       - Ground Response Analysis (DEEPSOIL, PySeismoSoil)
    
        - title: Validation and Enhancement of a 3D Physics-Based Ground Motion Simulation Platform for Seismic Hazard Quantification in the Korean Peninsula
          company: 'R&D Management Agency :Korea Institute of Science and Technology Information, Participant'
          date_start: '2023-01-01'
          date_end: ''
          description: |2
                       - Enhancement of a 3D Velocity Model of the southeastern part of the Korean Peninsula
                       - Characterization of Ground Motion Amplification Effect using Ambient Vibration and 
                         Regional Earthquakes in Low Seismicity Regions
    
    
        - title: Characterization of Ground Motion Amplification Effect using Ambient Vibration and Regional Earthquakes in Low Seismicity Regions
          company: 'R&D Management Agency : National Research Foundation of Korea, Assistant Researcher'
          date_start: '2020-06-01'
          date_end: '2023-02-28'
          description: |2
                        - Geophysical Exploration (HVSR, Surface Wave Inversion)
                        - Data Analysis
                        - Development of a fundamental frequency map of the southeastern
                          part of the Korean Peninsula (Kriging)
    
        - title: Experimental Results and Analysis of Active Test in the Testbed Area for High-Resolution Seismic Observation Network Expansion
          company: 'R&D Management Agency : Korea Meteorological Institute, Student Researcher'
          date_start: '2022-10-31'
          date_end: '2022-11-30'
          description: |2
                        - Geophysical Exploration (HVSR, Surface Wave Inversion)
                        - Data Analysis
        - title: Collection of Ground Information for the Establishment of Ground Motion Simulation in Busan, South Korea
          company: 'R&D Management Agency : Korea Institute of Science and Technology Information, Student Researcher'
          date_start: '2020-06-01'
          date_end: '2022-08-31'
          description: |2
                        - Geophysical Exploration (HVSR, Surface Wave Inversion)
                        - Data Analysis
                        - Development of a 3D Velocity Model of the southeastern part of
                          the Korean Peninsula for Ground Motion Simulation
    design:
      columns: '1'

    

  - block: features
    id: features
    content:
      title: Skills
      items:
        - name: Programming Language
          description: |
              Python (Obspy, Scipy, Basemap, PyKrige)
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
              Surface Wave Inversion, HVSR
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
        - title: Validation of Hybrid Ground Motion Simulation for Engineering Application in South Korea
          company: Future Directions Physics-Based Ground-Motion Modeling, Seismological Society of America
          company_url: ''
          company_logo: ''
          location: Vancouver, Canada
          date_start: '2023-10-13'
          date_end: '2023-10-13'
          description: S.Jeong, J.Kim, J.Oh, S.Bae and B.Bradley
    
        - title: Simplified 3D Basin Velocity Model of the Nakdonggang Delta Region, South Korea, Developed by HVSR and MAM
          company: Future Directions Physics-Based Ground-Motion Modeling, Seismological Society of America
          company_url: ''
          company_logo: ''
          location: Vancouver, Canada
          date_start: '2023-10-12'
          date_end: '2023-10-12'
          description: S.Jeong, J.Kim, G.Heo and D.Kwak
    
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

    



  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: Please contact me by follwing e-mail.
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
