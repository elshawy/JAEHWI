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
          date_start: '2025-07-01'
          description: 'Cho, Y. Ahn, S. Lee, J. Kim, J. Kim, B. Jeong, S.(doi : https://doi.org/10.1016/j.kscej.2024.100148)'
          organization: KSCE Journal of Civil Engineering
          organization_url:  
          title: Characteristics of ground motions in the Jeju Island during the 2021 Ml4. 9 Jeju earthquake, South Korea
          url: ''
    
        - date_end: ''
          date_start: '2025-01-01'
          description: 'Oh, J. Kim, J. Jeong, S.'
          organization: Journal of the Earthquake Engineering Society of Korea
          organization_url:  
          title: Scenario-Based Liquefaction Assessment of the Nakdonggang Delta Area Using Synthetic Ground Motions
          url: ''
    
        - date_end: ''
          date_start: '2025-01-01'
          description: 'Kim, J. Bae, SE. Bradley, BA. Jeong, S.'
          organization: Journal of the Earthquake Engineering Society of Korea
          organization_url:  
          title: Broadband Hybrid Ground Motion Simulation for Earthquake Engineering Applications in South Korea
          url: ''
    
        - date_end: ''
          date_start: '2024-09-01'
          description: 'Kim, J. OH, J. Jeong, S.'
          organization: Journal of the Earthquake Engineering Society of Korea
          organization_url:  
          title: Ground Motion Simulation of Scenario Earthquakes in the Nakdonggang Delta Region using a Broadband Hybrid Method and Site Response Analysis
          url: ''

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
          date_end: '2024-03-01'
          description: |2
                        - Review of Current Alert and Forecasting Criteria in Korea and Abroad
                        - Investigation of the Operation Patterns and Characteristics of the Seismic Observation Stations
                        - Comparison of Real-Time Seismic Information Processing Algorithms
    
        - title: Determining Design Ground Motion for the Nakdonggang Delta Region Using Broadband Hybrid Ground Motion Simulation
          company: 'R&D Management Agency : Changwon National University, Principal Investigator'
          date_start: '2023-03-01'
          date_end: '2024-03-01'
          description: |2
                       - Collection of Data Related to Current Seismic Design Standards in South Korea and Abroad
                       - Broadband Hybrid Ground Motion Simulation (Virtual Earthquake Scenario Setup and Execution)
                       - Ground Response Analysis (DEEPSOIL, PySeismoSoil)
    
        - title: Validation and Enhancement of a 3D Physics-Based Ground Motion Simulation Platform for Seismic Hazard Quantification in the Korean Peninsula
          company: 'R&D Management Agency :Korea Institute of Science and Technology Information, Participant'
          date_start: '2023-01-01'
          date_end: '2024-03-01'
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
              Python
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
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: Please contact me by follwing e-mail.
      text:    
      # Contact (add or remove contact options as necessary)
      email: jaehwi.kim@pg.canterbury.ac.nz
      address:
        
        city: Christchurch
        region: Canterbury
        postcode: ''
        country: New Zealand
        
      
    design:
      columns: '2'
---
