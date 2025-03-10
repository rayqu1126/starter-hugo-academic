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

        - title: Graduate Research Assistant
          company: Los Alamos National Laboratory
          company_url: 'https://www.lanl.gov'
          company_logo:
          location: Los Alamos, NM
          date_start: '2024-06-03'
          date_end: '2024-08-09'
          description: Research internship in the Group of Applied Mathematics and Plasma Physics (T-5). Applied model order reduction to stochastic fintie volume methods for uncertainty quantification in stochastic PDE systems. 

        - title: Undergraduate & Postbaccalaureate Research Assistant
          company: Physical Mathematics Laboratory
          company_url: 'https://pml.unc.edu'
          company_logo: 
          location: Chapel Hill, NC
          date_start: '2019-10-01'
          date_end: '2022-08-01'
          description: Studied active sprintronics enabling bistability-based computations in hydrodymanic spin lattices (HSLs).
    design:
      columns: '2'
   
  - block: markdown
    id: conference
    content:
      title: Conference and Talks
      text: "Upcoming: 2025 SIAM CSE, 2025 ICOSAHOM, 2025 USNCCM18<br>Nov 2024, Houston, TX: CMOR Grad Seminar (talk)<br>Oct, 2024, Houston, TX: RTG-NASC Annual Workshop ([talk](uploads/RTG_Workshop_24.pdf))<br>Sep 2024, Houston, TX: Master's Thesis Defense<br>Sep 2024, La Jolla, CA: Model Order Reduction and Surrogate Modeling ([poster](uploads/Poster_MORe24.pdf))<br>Jul 2024, Vancouver, Canada: WCCM-PANACM (talk)<br>Apr 2024, Houston, TX: RTG-NASC Ranch Retreat (talk)<br>Mar 2024, Houston, TX: Finite Element Rodeo (talk, [photo](https://ferodeo2024.rice.edu/photos), [news](https://engineering.rice.edu/news/finite-element-rodeo-returns-rice))<br>Feb 2024, Houston, TX: CMOR Grad Seminar (talk)<br>Nov 2023, Lafayette, LA: SIAM TX-LA 6th Annual Meeting (poster)<br>Oct 2023, Houston, TX: RTG-NASC Annual Workshop (poster)<br>Mar 2023, College Station, TX: Finite Element Rodeo<br>Nov 2022, Houston, TX: SIAM TX-LA 5th Annual Meeting"
    design:  
      columns: '2'
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: Ray.Qu@rice.edu
      address:
        street: Duncan Hall 2118, 6100 Main St. -MS 134
        city: Houston
        region: TX
        postcode: '77005'
        country: United States
        country_code: US
      directions: My office (#2118) is located on the second floor of [Anne and Charles Duncan Hall](https://www.cs.rice.edu/~keith/DuncanHall/).
      office_hours:
      - 'It is always welcome to stop by.'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
