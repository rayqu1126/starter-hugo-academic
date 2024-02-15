---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-20
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 
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
        - title: Graduate Research Assistant
          company: Chan Research Group
          company_url: 'https://jlchan.github.io'
          company_logo:
          location: Houston, TX
          date_start: '2023-01-01'
          date_end: ''
          description: Extending reduced order modeling of nonlinear conservation laws from finite volume methods to discontinuous Galerkin methods with new hyper reduction techniques.

        - title: Undergraduate & Postbaccalaureate Research Assistant
          company: Physical Math Lab
          company_url: 'https://pml.unc.edu'
          company_logo: 
          location: Chapel Hill, NC
          date_start: '2019-10-01'
          date_end: '2022-08-01'
          description: Studied active spinwaves in hydrodymanic spin lattices (HSLs) with theoretical development and numerical experiments.
    design:
      columns: '2'
    
  - block: markdown
    id: service
    content:
      title: Academic Service
      text: "[RTG in Numerical Mathematics & Scientific Computing (NASC)](https://rtg-nasc.rice.edu/) <br> 2023-2024, Rice CMOR Grad Seminar Chair"
    design:  
      columns: '2'
    
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: "CMOR 302 Matrix Analysis (FA 23, Teaching Assistant)<br>CAAM 382 Stochastic Models (SP 23, Grader)<br>CAAM 378 Intro to OR and Optimization (FA 22, Grader)"
    design:  
      columns: '2'

   
  - block: markdown
    id: conference
    content:
      title: Conference and Talks
      text: "Mar 2024, Houston, TX: CMOR Grad Seminar ([talk](uploads/CMOR_seminar_2024.pdf))<br>Nov 2023, Lafayette, LA: SIAM TX-LA 6th Annual Meeting ([poster](uploads/poster_DGROM.pdf))<br>Oct 2023, Houston, TX: RTG-NASC Annual Workshop ([poster](uploads/poster_DGROM.pdf))<br>Mar 2023, College Station, TX: Finite Element Rodeo (attendee)<br>Nov 2022, Houston, TX: SIAM TX-LA 5th Annual Meeting (attendee)"
    design:  
      columns: '2'
 
  - block: collection
    id: publication
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: Ray.Qu@rice.edu
      phone: N/A
      address:
        street: Duncan Hall 2118, 6100 Main St. -MS 134
        city: Houston
        region: TX
        postcode: '77005'
        country: United States
        country_code: US
      directions: My office (#2118) is located on the second floor of Anne and Charles Duncan Hall.
      office_hours:
      - 'No office hour is scheduled at this time.'
      - 'It is always welcome to stop by and chat with me.'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
