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
        - title: Assistant Professor
          company: Yonsei University
          company_url: 'https://yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2024-03-01'
          date_end: ''
          description: |2-
              * Department of System Semiconductor Engineering
              * School of Electrical and Electronic Engineering
              * Research Topics: Energy-Efficient CPU/GPU Microarchitectures, High-Performance System Architectures, Near-Data Processing, Interconnect Technologies
        - title: Postdoctoral Research Associate
          company: University of Illinois Urbana-Champaign
          company_url: 'https://illinois.edu/'
          company_logo: ''
          location: Illinois, USA
          date_start: '2022-09-01'
          date_end: '2024-02-29'
          description: |2-
              * Coordinated Science Lab (CSL)
              * Principal Investigator (PI): Professor Nam Sung Kim
              * Research Topics: Architectural Optimizations for Datacenters, CXL-Based Device Architectures, Smart-I/O Devices (SmartSSD, SmartNIC, etc.)
        - title: Research Professor
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2021-09-01'
          date_end: '2022-08-31'
          description: |2-
              * BK21 Y-BASE R&E Institute, Department of Electrical and Electronic Engineering
              * Research Topics: Energy-Efficient CPU/GPU Microarchitectures, Processing-in-Memory (PIM) Architectures
        - title: Engineer/Staff Engineer
          company: Samsung Electronics
          company_url: 'https://www.samsung.com/'
          company_logo: ''
          location: Hwaseong-si, Gyeonggi-do, Korea
          date_start: '2020-03-01'
          date_end: '2021-08-31'
          description: |2-
              * Advanced Solution Development Team, Memory Business
              * Research Topics: CXL-Based Accelerator/Memory Expansion Device Architectures, Computational Storage Drive (SmartSSD 2.0) SoC Architecture
        - title: Graduate Research Assistant
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2014-03-01'
          date_end: '2020-02-28'
          description: |2-
              * Embedded Systems and Computer Architecture Lab (eSCaL)
              * Advisor: Professor Won Woo Ro
              * Research Topics: Energy-Efficient CPU/GPU Microarchitectures, Multi-Core Architectures
        - title: Teaching Assistant
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2014-03-01'
          date_end: '2020-02-28'
          description: |2-
              * Undergraduate courses: Computer Architecture (EEE3530, 14-1st, 16-1st), Electrical and Electronic Engineering Experiments: Fundamentals (EEE2111, 14-2nd, 15-2nd), Graduation Research (15-1st)
              * Graduate courses: Advanced Computer Architecture (E6501, 17-1st), System Design and Applications Lab (EEE6611, 18-1st, 18-2nd)
        - title: Undergraduate Research Assistant
          company: Yonsei University
          company_url: 'https://www.yonsei.ac.kr/'
          company_logo: ''
          location: Seoul, Korea
          date_start: '2013-08-01'
          date_end: '2014-02-28'
          description: |2-
              * Embedded Systems and Computer Architecture Lab (eSCaL)
              * Advisor: Professor Won Woo Ro
              * Research Topics: Exploiting Back-end Fusion in Multi-Core Processors
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
  - block: collection
    id: events
    content:
      title: Recent & Upcoming Events
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: recent
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
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
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
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
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: markdown
    id: section-1
    content:
      title: Scholarships and Awards
      subtitle: ""
      text: |2-
        #### **[2021.11]  Encouragement Prize at the Outstanding Patent Award (SK Hynix)**
        * Memory Device Including a Plurality of Area Having Different Refresh Periods, Memory Controller Controlling the Same and Memory System Including the Same
        * US patent, Registered in 2022.03.15 (Application no: 16/988478, Registration no: 11276452)
        #### **[2020.02]  Bronze Prize at the 26th Samsung Humantech Paper Award (Samsung Electronics)**
        * Ipoom Jeong, Seihoon Park
        * CASINO Core Microarchitecture: Generating Out-of-Order Schedules Using Cascaded In-Order Scheduling Windows
        #### **[2019.11]  Excellent Graduate Researcher Scholarship (Yonsei University)**
        #### **[2018.02]  Encouragement Prize at the 24th Samsung Humantech Paper Award (Samsung Electronics)**
        * Ipoom Jeong, Changmin Lee
        * Cg-CMT: Expanding Instruction Window via Coarse-Grained Instruction Commit
        #### **[2010.03 - 2014.02]  National Scholarship for Science and Engineering (KOSAF)**
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: section-2
    content:
      title: Activities
      subtitle: ""
      text: |2-
        #### **Tutorial Organizer**
        * On-chip Accelerators in 4th Gen Intel® Xeon® Scalable Processors: Features, Performance, Use Cases, and Future!
        * 50th International Symposium on Computer Architecture (ISCA 2023)
        #### **Invited Talk**
        * Institute of Electronics and Information Engineers (IEIE) SoC Conference 2025
        * Korean Institute of Information Scientists and Engineers(KIISE) CSS Conference 2025
        * Institute of Electronics and Information Engineers (IEIE) SoC Conference 2024
        #### **Conference Chair**
        * Excursion chair: IEEE/ACM International Symposium on Microarchitecture (MICRO) 2025
        * Publication chair: Korean Institute of Information Scientists and Engineers(KIISE) CSS Conference 2025
        * Session chair: Artificial Intelligence Circuits and Systems (AICAS) 2022
        #### **External Reviewer Committee**
        * IEEE/ACM International Symposium on Microarchitecture (MICRO) 2025
        * IEEE Transactions on Emerging Topics in Computing (TETC)
        * IEEE Transactions on Computers (TC)
        * ACM Transactions on Storage (TOS)
        * IEEE Journal on Emerging and Selected Topics in Circuits and Systems (JETCAS)
        * IEEE Computer Architecture Letters (CAL)
        * ACM Transactions on Architecture and Code Optimization (TACO)
        * Microprocessors and Microsystems
        
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Thank you for visiting Ipoom Jeong's website!
      # Contact (add or remove contact options as necessary)
      email: ipoom@yonsei.ac.kr
      phone: 02-2123-5853
      #appointment_url: 'https://calendly.com'
      address:
        street: 50, Yonsei-ro, Seodaemun-gu
        city: Seoul
        postcode: '03722'
        country: Republic of Korea
        country_code: KR
      coordinates:
        latitude: '37.335903'
        longitude: '126.561969'
      #directions: Enter CSL (Coordinated Science Laboratory) building and take the stairs to Office 456 on Floor 4
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
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
