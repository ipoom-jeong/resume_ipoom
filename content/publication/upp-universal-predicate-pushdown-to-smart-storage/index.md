---
publication_types:
  - "1"
authors:
  - admin
  - Jinghan Huang
  - Chuxuan Hu
  - Dohyun Park
  - Jaeyoung Kang
  - Nam Sung Kim
  - Yongjoo Park
publication: ACM/IEEE International Symposium on Computer Architecture (ISCA, accepted)
abstract: "In large-scale analytics, in-storage processing (ISP) can significantly
boost query performance by letting ISP engines (e.g., FPGAs) preselect only the relevant data before sending them to databases.
This reduces the amount of not only data transfer between storage
and host, but also database computation, facilitating faster query
processing. However, existing ISP solutions cannot effectively support a wide range of modern analytical queries because they only
support simple combinations of frequently used operators (e.g., =,
<), particularly on fixed-length columns. As modern databases allow filter predicates to include numerous operators/functions (e.g.,
dateadd) compatible with diverse data formats (and their complex
combinations), it becomes more challenging for existing approaches
to accelerate such queries efficiently.
To address the limitations, we propose a new ISP approach, called
Universal Predicate Pushdown (UPP), that can accelerate modern
analytical databases, leveraging hardware/software co-design for a
high level of flexibility. Our core insight is that instead of programming for individual filter operators/functions, we should devise a
compact instruction set architecture (ISA) tailored explicitly for
predicate pushdown. The software (i.e., database) layer recognizes
and compiles various general filters (called a universal predicate) to
a set of UPP-compliant instructions, which are then processed efficiently by FPGA using bitwise comparisons, leveraging lightweight
metadata. In our experiments with a 100 GB TPC-H dataset, UPP
running on SmartSSD could speed up Spark’s end-to-end query
performance by 1.2×–7.9× without changing input data formats."
draft: false
url_pdf: ""
featured: true
summary: "This work introduces Universal Predicate Pushdown (UPP), a flexible in-storage processing (ISP) approach that accelerates modern analytical queries by offloading complex filter predicates to FPGA-based storage using a custom instruction set. By efficiently handling diverse operators and data formats, UPP achieves 1.2×–7.9× speedups on Spark queries over a 100 GB TPC-H dataset without requiring changes to input data formats."
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
url_tutorial: ""
title: "UPP: Universal Predicate Pushdown to Smart Storage"
tags:
  - SSD
  - In-storage processing
  - Database
  - Systems
image:
  filename: "upp.png"
  focal_point: SMART
  preview_only: false
  caption: ""
date: 2025-04-08T07:41:54.531Z
url_slides: ""
url_poster: ""
url_code: ""
---
