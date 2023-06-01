---
title: "[UIUC HACC Seminar] VersatileSSD: Breaking I/O Barrier by Leveraging SmartSSD"
abstract: "Modern server systems are facing the challenge of meeting the
  increasingly demanding performance requirements of applications that process
  massive amounts of data, such as databases, machine learning, and data
  analytics. Solid-state drives (SSDs) have grown in popularity due to their
  ability to significantly reduce the time required for transferring huge
  amounts of data, resulting in a shift in the system bottleneck from data
  transfer to interconnect bandwidth and operating system overhead. However, as
  the PCIe places limitations on simultaneous I/O device access, the scalability
  of the system is limited when multiple I/O devices are servicing independent
  contexts of I/O operations. This issue, along with the long-latency
  interconnect bus data transfer, has led to the development of SmartSSD, which
  employs near-data processing (NDP) to move computations closer to the location
  where the data is stored. This presentation outlines our vision for leveraging
  SmartSSD to maximize its computing potential and versatility in the context of
  NDP. Specifically, we will discuss two approaches that we are currently
  exploring: 1) Universal predicate pushdown and 2) OS page cache expander. We
  will present the high-level concepts behind these approaches and outline our
  development plan, which we believe will pave the way for integrating SmartSSD
  into mainstream server systems."
location: Virtual Seminar
date: 2023-03-08T16:00:00.000Z
all_day: false
slides: null
draft: false
url_pdf: ""
summary: UIUC AMD-Xilinx Heterogeneous Compute Cluster (HACC) Seminar
date_end: 2023-03-08T18:00:00.000Z
event_url: https://xilinx-center.csl.illinois.edu/seminars/
featured: false
authors:
  - Ipoom Jeong
url_video: ""
url_slides: ""
address: ""
event: UIUC AMD-Xilinx Heterogeneous Compute Cluster (HACC) Seminar
publishDate: 2023-05-31T06:13:12.919Z
tags: []
projects: null
image:
  caption: ""
  focal_point: Right
  filename: featured.png
url_code: ""
---
<!---
Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page.
--->
