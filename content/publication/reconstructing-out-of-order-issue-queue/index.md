---
title: Reconstructing Out-of-Order Issue Queue
publication_types:
  - "1"
authors:
  - admin
  - Jiwon Lee
  - Myung Kuk Yoon
  - Won Woo Ro
publication: IEEE/ACM International Symposium on Microarchitecture (MICRO)
abstract: >-
  Out-of-order cores provide high performance at the cost of energy efficiency.
  Dynamic scheduling is one of the major contributors to this: generating highly
  optimized issue schedules considering both data dependences and underlying
  execution resources, but relying heavily on complex wakeup and select
  operations of an out-of-order issue queue (IQ). For decades, researchers have
  proposed several complexity-effective dynamic scheduling schemes by leveraging
  the energy efficiency of an in-order IQ. However, they are either costly or
  not capable of delivering sufficient performance to substitute for a
  conventional wide-issue out-of-order IQ. 


  In this work, we revisit two previous designs: one classical dependence-based design and the other state-of-the-art readiness-based design. We observe that they are complementary to each other, and thus their synergistic integration has the potential to be a good alternative to an out-of-order IQ. We first combine these two designs, and further analyze the main architectural bottlenecks that incur the underutilization of aggregate issue capability, thereby limiting the exploitation of instruction-level and memory-level parallelisms: 1) memory dependences not exposed by the register-based dependence analysis and 2) wide and shallow nature of dynamic dependence chains due to the long-latency memory accesses. To this end, we propose Ballerino, a novel microarchitecture that performs balanced and cache-miss-tolerable dynamic scheduling via a complementary combination of cascaded and clustered in-order IQs. Ballerino is built upon three key functionalities: 1) speculatively filtering out ready-at-dispatch instructions, 2) eliminating wasteful wakeup operations via a simple steering technique leveraging the awareness of memory dependences, and 3) reacting to program phase changes by allowing different load-dependent chains to share a single IQ while guaranteeing their out-of-order issue. The net effect is minimal scheduling energy consumption per instruction while providing comparable scheduling performance to a fully out-of-order IQ. In our analysis, Ballerino achieves comparable performance to an 8-wide out-of-order core by using twelve in-order IQs, improving core-wide energy efficiency by 20%.
draft: false
url_pdf: https://ieeexplore.ieee.org/document/9923800
featured: true
tags:
  - CPU
  - Microarchitecture
  - Dynamic Scheduling
  - Energy Efficiency
summary: "In this work, we propose an energy-efficient microarchitecture named
  Ballerino, carrying out BALanced and cache-miss toLERable dynamic scheduling
  via cascaded and clustered IN-Order IQs. The proposed microarchitecture is
  built upon three key principles that drive dynamic scheduling: instruction
  readiness, memory/register dependences, and oldest-first selection."
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
doi: 10.1109/MICRO56248.2022.00023
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Ballerino core microarchitecture overview
date: 2022-10-01T02:57:06.623Z
url_slides: ""
url_poster: ""
url_code: ""
---
