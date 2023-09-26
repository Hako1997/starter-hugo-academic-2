---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

Sections: 
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    id: edu
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD in Electrical Engineering
          company: The University of Hong Kong
          company_url: ''
          company_logo: HKU
          location: Hong Kong SAR, China
          date_start: '2018-09-01'
          date_end: '2022-08-31'
        - title: BSc in Electrical Engineering
          company: Huazhong University of Science and Technology
          company_url: ''
          company_logo: HUST
          location: Wuhan, China
          date_start: '2014-09-01'
          date_end: '2018-06-30'
    design:
      columns: '2'
  - block: experience
    id: exp
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
        - title: Postdoctoral Research Fellow
          company: The University of Hong Kong
          company_url: ''
          company_logo: HKU
          location: Hong Kong SAR, China
          date_start: '2022-09-01'
          date_end: ''
        - title: Intern
          company: Dispatching & Control Center, State Grid Coorporation of China
          company_url: ''
          company_logo: SG
          location: Hunan, China
          date_start: '2017-07-31'
          date_end: '2017-08-31'
    design:
      columns: '2'
  - block: collection
    id: pub
    content:
      title: Publications
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
      title: Invited Talks (Recent & Upcoming)
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: yjli@eee.hku.hk
      # phone: 852 61949185
      directions: CYC 801, The University of Hong Kong
      address:
        street: Polfulam Road
        city: Central and Western District
        region: Hong Kong SAR
        postcode: '999077'
        country: China
        country_code: CN
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
