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
        - title: Postdoctoral Research Associate
          company: University of Illinois Urbana-Champaign
          company_url: 'https://illinois.edu/'
          company_logo: ''
          location: Illinois, USA
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              * Coordinated Science Lab (CSL)
              * Principal Investigator (PI): Professor Nam Sung Kim
              * Research Topics:
        - title: Research Professor
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2021-09-01'
          date_end: '2022-08-31'
          description: |2-
              * BK21 Y-BASE R&E Institute, Department of Electrical and Electronic Engineering
              * Research Topics: Energy-Efficient CPU/GPU Microarchitectures
        - title: Engineer/Staff Engineer
          company: Samsung Electronics
          company_url: 'https://www.samsung.com/'
          company_logo: ''
          location: Hwaseong-si, Gyeonggi-do, Korea
          date_start: '2020-03-01'
          date_end: '2021-08-31'
          description: |2-
              * Advanced Solution Development Team, Memory Business
              * Research Topics: CXL-Based Accelerator/Memory Expansion Devices, SmartSSD 2.0
        - title: Research Assistant
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2014-03-01'
          date_end: '2020-02-28'
          description: |2-
              * Embedded Systems and Computer Architecture Lab (eSCaL)
              * Advisor: Professor Won Woo Ro
              * Research Topics:
        - title: Teaching Assistant
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: 'Yonsei-University'
          location: Seoul, Korea
          date_start: '2014-03-01'
          date_end: '2020-02-28'
          description: |2-
              * Undergraduate courses: Computer Architecture (EEE3530, 14-1st, 16-1st), Electrical and Electronic Engineering Experiments: Fundamentals (EEE2111, 14-2nd, 15-2nd), Graduation Research (15-1st)
              * Graduate courses: Advanced Computer Architecture (E6501, 17-1st), System Design and Applications Lab (EEE6611, 18-1st, 18-2nd)
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
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
        Thank you for visiting Ipoom Jeong's website!
      # Contact (add or remove contact options as necessary)
      email: ipoom@illinois.edu
      phone: +1 (217) 778-8808
      #appointment_url: 'https://calendly.com'
      address:
        street: 1308 W Main St
        city: Urbana
        region: IL
        postcode: '61801'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.115030'
        longitude: '-88.226570'
      directions: Enter CSL (Coordinated Science Laboratory) building and take the stairs to Office 456 on Floor 4
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
      autolink: true
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
