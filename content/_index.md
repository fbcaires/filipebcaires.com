---
date: "2023-08-27"
sections:
- block: about.biography
  content:
    title: Welcome!
    username: admin
  id: about
# - block: features
 # content:
 #   items:
  #  - description: 90%
  #    icon: r-project
  #    icon_pack: fab
  #    name: R
  #  - description: 100%
  #    icon: chart-line
  #    icon_pack: fas
  #    name: Statistics
  #  - description: 10%
  #    icon: camera-retro
  #    icon_pack: fas
  #    name: Photography
  #  title: Skills
#- block: experience
 # content:
 #   date_format: Jan 2006
 #   items:
  #  - company: GenCoin
  #    company_logo: org-gc
  #    company_url: ""
  #    date_end: ""
  #    date_start: "2021-01-01"
  #    description: |2-
  #       Responsibilities include:

   #       * Analysing
   #       * Modelling
   #       * Deploying
   #   location: California
   #   title: CEO
   # - company: University X
   #   company_logo: org-x
   #   company_url: ""
   #   date_end: "2020-12-31"
   #   date_start: "2016-01-01"
   #   description: Taught electronic engineering and researched semiconductor physics.
   #   location: California
   #   title: Professor of Semiconductor Physics
   # title: Experience
  #design:
    #columns: "2"
#- block: collection
#  content:
#    filters:
#      exclude_featured: true
#      folders:
#      - publication
    # text: |-
    #  {{% callout note %}}
    #  Quickly discover relevant content by [filtering publications](./publication/).
    #  {{% /callout %}}
#    title: Research
# design:
#   columns: "2"
#   view: card
#  id: research
- block: markdown
  content:
    title: Research
    text: |
      {{< mypublications >}}
  design:
    columns: "1"
  id: research
- block: markdown
  content:
    title: Teaching
    text: |
      {{< myteaching >}}
  design:
    columns: "2"
  id: teaching
#- block: accomplishments
#  content:
#    date_format: Jan 2006
#    items:
#    - certificate_url: ""
#      date_end: "2024-02-01"
#      date_start: "2024-03-31"
#      description: "TA to Andrea Mattozzi"
#      organization: PhD in Economics EUI
#      organization_url: https://www.eui.eu/en/academic-units/department-of-economics
#      title: Microeconomics III - Information Economics and Social Choice
#      url: ""
#    - certificate_url: ""
#      date_end: "2023-02-28"
#      date_start: "2022-10-01"
#      description: "TA to Sule Alan and Tom Crossley"
#      organization: PhD in Economics EUI
#      organization_url: https://www.eui.eu/en/academic-units/department-of-economics
#      title: Statistics and Econometrics II - Econometrics of Microdata
#      url: ""
#    - certificate_url: ""
#      date_end: "2020-06-01"
#      date_start: "2020-01-01"
#      description: "Grader to Pedro Raposo"
#      organization: MSc in Economics CATOLICA-LISBON
#      organization_url: https://www.clsbe.lisboa.ucp.pt/msc-economics/overview
#      title: Microeconometrics
#      url: ""
#    - certificate_url: ""
#      date_end: "2020-03-01"
#      date_start: "2018-09-01"
#      description: "TA and Grader to Hugo Reis"
#      organization: MSc in Economics CATOLICA-LISBON
#      organization_url: https://www.clsbe.lisboa.ucp.pt/msc-economics/overview
#      title: Econometrics II
#      url: ""
#    - certificate_url: ""
#      date_end: "2020-03-01"
#      date_start: "2018-09-01"
#      description: "TA and Grader to Hugo Reis"
#      organization: MSc in Economics CATOLICA-LISBON
#      organization_url: https://www.clsbe.lisboa.ucp.pt/msc-economics/overview
#      title: Economics of Education
#      url: ""
#    subtitle: Experience
#    title: Teaching
#  design:
#    columns: "2"
#  id: teaching
#- block: collection
#  content:
#    count: 5
#    filters:
#      author: ""
#      category: ""
#      exclude_featured: false
#      exclude_future: false
#      exclude_past: false
#      folders:
#      - post
#      publication_type: ""
#      tag: ""
#    offset: 0
#    order: desc
#    subtitle: ""
#    text: ""
#    title: Recent Posts
#  design:
#    columns: "2"
#    view: compact
#  id: posts
# - block: portfolio
 # content:
 #   buttons:
 #   - name: All
 #     tag: '*'
 #   - name: Deep Learning
 #     tag: Deep Learning
 #   - name: Other
 #     tag: Demo
 #   default_button_index: 0
 #   filters:
 #     folders:
 #     - project
 #   title: Projects
 # design:
 #   columns: "1"
 #   flip_alt_rows: false
 #   view: showcase
 # id: projects
#- block: markdown
 # content:
 #   subtitle: ""
 #   text: '{{< gallery album="demo" >}}'
 #   title: Gallery
 # design:
 #   columns: "1"
# - block: collection
#  content:
#    filters:
#      featured_only: true
#      folders:
#      - publication
#    title: Featured Publications
#  design:
#    columns: "2"
#    view: card
#  id: featured
# - block: collection
#  content:
#    filters:
#      folders:
#      - event
#    title: Recent & Upcoming Talks
#  design:
#    columns: "2"
#    view: compact
#  id: talks
# - block: tag_cloud
#  content:
#    title: Popular Topics
#  design:
#    columns: "2"
- block: contact
  content:
    address:
      city: Fiesole
      country: Italia
      country_code: IT
      postcode: "50014"
      region: Toscana
      street: Via delle Fontanelle, 18
    # appointment_url: https://calendly.com
    # autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: fbcaires
    # - icon: skype
    #  icon_pack: fab
    #  link: skype:echo123?call
    #  name: Skype Me
    #- icon: video
    #  icon_pack: fas
    #  link: https://zoom.com
    #  name: Zoom Me
    email: filipe.b.caires@eui.eu
    # form:
    #  formspree:
    #    id: null
    #  netlify:
    #    captcha: false
    #  provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    phone: (+351) 918949665 
    subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #  ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
