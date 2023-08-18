---
title: "LADIO: Leakage-Aware Direct I/O for I/O-Intensive Workloads"
publication_types:
  - "2"
authors:
  - admin
  - Jiaqi Lou
  - Yongseok Son
  - Yongjoo Park
  - Yifan Yuan
  - Nam Sung Kim
publication: "IEEE Computer Architecture Letters (Volume: 22, Issue: 2)"
abstract: >-
  The advancement in I/O technology has posed an unprecedented demand for
  high-performance processing on I/O data,

  leading to the development of Data Direct I/O (DDIO) technology. DDIO improves I/O processing efficiency by directly injecting all

  inbound I/O data into the last-level cache (LLC) in cooperation with any type of I/O device. Nonetheless, it has been observed that

  DDIO can cause significant interference between I/O applications inside the LLC, resulting in the degradation of system performance.

  Especially, in this paper, we demonstrate that storage I/O on modern high-performance NVMe SSDs hardly benefits from DDIO,

  sometimes causing inefficient use of the shared LLC due to the “leaky DMA problem”. To address this problem, we propose LADIO, an

  adaptive approach that mitigates inter-application interference by dynamically controlling the DDIO functionality and reallocating LLC

  ways based on the leakage and locality of storage I/O data, respectively. In scenarios with heavy I/O interference, LADIO improves the

  throughput of network-intensive applications by 20% while maintaining that of storage-intensive applications.
draft: false
url_pdf: https://ieeexplore.ieee.org/document/10171430
featured: true
tags:
  - DDIO
  - Datacenter
  - Last-Level Cache
  - I/O
  - Storage
  - Network
  - CPU
doi: 10.1109/LCA.2023.3290427
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: This paper presents LADIO (Leakage-Aware Direct I/O), an adaptive
  direct cache access mechanism (a.k.a., Data Direct I/O, DDIO) to alleviate the
  inter-I/O (between network I/O and storage I/O) interference problem in modern
  datacenter servers.
date: 2023-07-01T00:00:00.000Z
---
