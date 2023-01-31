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
        - title: Doctoral Candidate
          company: HelmholtzAI, Kilbertus Group
          company_url: 'https://www.helmholtz.ai/themenmenue/our-research/research-groups/kilbertus-group/index.html'
          # company_logo: helmholtzai
          location: Munich
          date_start: '2020-11-01'
          date_end: ''
          description:
              Working on causal inference in general.
        - title: Data Scientist and Machine Learning Researcher
          company: Steering Lab (Horváth&Partners)
          company_url: ''
          #company_logo: steering lab
          location: Munich
          date_start: '2019-03-01'
          date_end: '2020-10-31'
          description: 
              Unsupervised time series classification and prediction.
        - title: Quantitative Financial Analyst
          company: risklab (Allianz Global Investors)
          company_url: ''
          #company_logo: risklab
          location: Munich
          date_start: '2016-10-01'
          date_end: '2019-02-28'
          description: 
              Automation of asset allocation.
        - title: Research Intern
          company: MEAG
          company_url: ''
          #company_logo: meag
          location: Munich
          date_start: '2016-01-01'
          date_end: '2016-09-30'
          description: 
              Research on Value-at-Risk Decomposition and Sensitivities.
        - title: Intern
          company: risklab (Allianz Global Investors)
          company_url: ''
          #company_logo: risklab
          location: Munich
          date_start: '2015-10-01'
          date_end: '2015-12-31'
          #description: 
          #    Risk-Management Overlay.
        - title: Intern
          company: PriceWaterhouseCoopers
          company_url: ''
          #company_logo: pwc
          location: Munich
          date_start: '2015-04-01'
          date_end: '2015-05-31'
          #description: 
          #    Risk-Management Overlay.
    design:
      columns: '2'
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
  - block: collection
    content:
      title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
      filters:
        folders:
          - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
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
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      #email: elisabeth.ailer@helmholtz-muenchen.de
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      #address:
      #  street: 450 Serra Mall
      #  city: Stanford
      #  region: CA
      #  postcode: '94305'
      #  country: United States
      #  country_code: US
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
