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
      [Download Teaching Evaluations (PDF)](/uploads/Caires_TeachingEvaluations.pdf)
      {{< myteaching >}}
  design:
    columns: "2"
  id: teaching
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
