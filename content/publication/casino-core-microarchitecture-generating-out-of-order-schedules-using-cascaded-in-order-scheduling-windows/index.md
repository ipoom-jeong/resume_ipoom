---
title: "CASINO Core Microarchitecture: Generating Out-of-Order Schedules Using
  Cascaded In-Order Scheduling Windows"
publication_types:
  - "1"
authors:
  - admin
  - Seihoon Park
  - Changmin Lee
  - Won Woo Ro
publication: IEEE International Symposium on High Performance Computer Architecture (HPCA)
abstract: >-
  The performance gap between in-order (InO) and out-of-order (OoO) cores comes
  from the ability to dynamically create highly optimized instruction issue
  schedules. In this work, we observe that a significant amount of performance
  benefit of OoO scheduling can also be attained by supplementing a traditional
  InO core with a small and speculative instruction scheduling window, namely
  SpecInO. SpecInO monitors a small set of instructions ahead of a conventional
  InO scheduling window, aiming at issuing ready instructions behind
  long-latency stalls. Simulation results show that SpecInO captures and issues
  62% of dynamic instructions out of program order. 


  To this end, we propose a CASINO core microarchitecture that dynamically and speculatively generates OoO schedules with near-InO complexity, using CAScaded IN-Order scheduling windows. A Speculative IQ (S-IQ) issues an instruction if it is ready, or otherwise passes it to the next IQ. At the last IQ, instructions are scheduled in program order along serial dependence chains. The net effect is OoO scheduling via collaboration between cascaded InO IQs. To support speculative execution with minimal cost overhead, we propose a novel register renaming technique that allocates free physical registers only to instructions issued from the S-IQ. The proposed core performs dynamic memory disambiguation via an on-commit value check by extending the store buffer already existing in an InO core. We further optimize energy efficiency by filtering out redundant associative searches performed by speculated loads. In our analysis, CASINO core improves performance by 51% over an InO core (within 10 percentage points of an OoO core), which results in 25% and 42% improvements in energy efficiency over InO and OoO cores, respectively.
draft: false
url_pdf: https://ieeexplore.ieee.org/document/9065575
featured: true
tags:
  - CPU
  - Microarchitecture
  - Dynamic Scheduling
  - Energy Efficiency
summary: In this work, we propose a CASINO core microarchitecture that
  dynamically and speculatively generates out-of-order instruction issue
  schedules with complexity close to in-order scheduling by leveraging CAScaded
  IN-Order scheduling windows.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
doi: 10.1109/HPCA47549.2020.00039
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: CASINO core microarchitecture overview
date: 2020-02-22T00:00:00.750Z
url_slides: ""
url_poster: ""
url_code: ""
---
