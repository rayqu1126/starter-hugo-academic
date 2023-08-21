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
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: 
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
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
        - 'to be arranged'
        - 'You are always welcome to stop by my office when I am available.'
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---
