---
publication_types:
  - "1"
authors:
  - Yan Sun
  - Yifan Yuan
  - Zeduo Yu
  - Reese Kuper
  - Chihun Song
  - Jinghan Huang
  - Houxiang Ji
  - Siddharth Agarwal
  - Jiaqi Lou
  - admin
  - Ren Wang
  - Jung Ho Ahn
  - Tianyin Xu
  - Nam Sung Kim
publication: IEEE/ACM International Symposium on Microarchitecture (MICRO)
abstract: >-
  The ever-growing demands for memory with larger capacity and higher bandwidth
  have driven recent innovations on memory expansion and disaggregation
  technologies based on Compute eXpress Link (CXL). Especially, CXL-based memory
  expansion technology has recently gained notable attention for its ability not

  only to economically expand memory capacity and bandwidth but also to decouple memory technologies from a specific memory interface of the CPU. However, since CXL memory devices have not been widely available, they have been emulated using DDR memory in a remote NUMA node. In this paper, for the first time, we comprehensively evaluate a true CXL-ready system based on the latest 4th-generation Intel Xeon CPU with three CXL memory devices from different manufacturers. Specifically, we run a set of microbenchmarks not only to compare the performance of true CXL memory with that of emulated CXL memory but also to analyze the complex interplay between the CPU and CXL memory in depth. This reveals important differences between emulated CXL memory and true CXL memory, some of which will compel researchers to revisit the analyses and proposals from recent work. Next, we identify opportunities for memory-bandwidth-intensive applications  to benefit from the use of CXL memory. Lastly, we propose a CXL-memory-aware dynamic page allocation policy, Caption to more efficiently use CXL memory as a bandwidth expander. We demonstrate that Caption can automatically converge to an empirically favorable percentage of pages allocated to CXL memory, which improves the performance of memory-bandwidth-intensive applications by up to 24% when compared to the default page allocation policy designed for traditional NUMA systems.
draft: false
url_pdf: https://dl.acm.org/doi/abs/10.1145/3613424.3614256
featured: true
summary: In this work, we evaluate true CXL-ready systems based on the latest
  4th-generation Intel Xeon CPU with three CXL memory devices from different
  manufacturers, which divulges important differences between emulated and true
  CXL memory devices. Based on these observations, we propose a CXL-memory-aware
  dynamic page allocation policy, Caption, to use CXL memory more efficiently.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
url_tutorial: ""
title: Demystifying CXL Memory with Genuine CXL-Ready Systems and Devices
tags:
  - CXL
  - memory
  - CPU
  - datacenter
image:
  filename: featured.png
  focal_point: SMART
  preview_only: false
  caption: 
date: 2023-10-25T18:08:56.908Z
url_slides: ""
url_poster: ""
url_code: ""
---
