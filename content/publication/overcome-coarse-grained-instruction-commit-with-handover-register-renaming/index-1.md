---
title: "LADIO: Leakage-Aware Direct I/O for I/O-Intensive Workloads"
publication_types:
  - "2"
authors:
  - admin
  - Changmin Lee
  - Keunsoo Kim
  - Won Woo Ro
publication: IEEE Computer Architecture Letters (Accepted)
abstract: >-
  The advancement in I/O technology has posed an unprecedented demand for
  high-performance processing on I/O data, leading to the development of Data
  Direct I/O (DDIO) technology. DDIO improves I/O processing efficiency by
  directly injecting all inbound I/O data into the last-level cache (LLC) in
  cooperation with any type of I/O device. Nonetheless, it has been observed
  that DDIO can cause significant interference between I/O applications inside
  the LLC, resulting in the degradation of system performance. Especially, in
  this paper, we demonstrate that storage I/O on modern high-performance NVMe
  SSDs hardly benefits from DDIO,

  sometimes causing inefficient use of the shared LLC due to the “leaky DMA problem”. To address this problem, we propose LADIO, an adaptive approach that mitigates inter-application interference by dynamically controlling the DDIO functionality and reallocating LLC ways based on the leakage and locality of storage I/O data, respectively. In scenarios with heavy I/O interference, LADIO improves the throughput of network-intensive applications by 20% while maintaining that of storage-intensive applications.
draft: false
url_pdf: https://ieeexplore.ieee.org/abstract/document/8807276
featured: true
tags:
  - CPU
  - Microarchitecture
  - Instruction Window
  - Energy Efficiency
summary: This paper proposes a leakage-aware Data Direct I/O (DDIO) control
  mechanism – LADIO – to alleviate the inter-I/O interference problems in
  datacenter server systems.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
doi: ""
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: OverCome core microarchitecture overview
date: 2023-06-15T14:31:42.940Z
url_slides: ""
url_poster: ""
url_code: ""
---
