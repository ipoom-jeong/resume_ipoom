---
title: Time Series Machine Learning Models for Precise SSD Access Latency Prediction
publication_types:
  - "2"
authors:
  - admin
  - Jiaqi Lou
  - Yongseok Son
  - Yongjoo Park
  - Yifan Yuan
  - Nam Sung Kim
publication: IEEE Computer Architecture Letters (accepted)
abstract: >-
  Solid State Drives (SSDs) have become the dominant storage solution over the
  past few years. A key component of SSDs is the controller, which manages
  communication between the host and flash memory, optimizing data transfer
  speeds, integrity, and lifespan. However, modern SSDs function as black boxes,
  as manufacturers do not disclose firmware and controller details. Meanwhile,
  read and write latencies are affected by various internal optimizations, such
  as wear-leveling and garbage collection, making precise latency prediction
  challenging. Existing approaches rely on trace-driven simulation or machine
  learning, but either (1) just classify operations into broad latency
  categories (e.g., fast or slow), including software stack overhead, or (2)
  make imprecise predictions while consuming significant system resources and
  time. For system simulation, latency predictions must be both fast and
  accurate, focusing solely on device-level delays excluding OS overhead, which
  is modeled separately. To

  tackle these challenges, this paper presents time series machine learning models to accurately predict hardware-only SSD latencies across diverse workloads. Our evaluation shows that the proposed model predicts 85%–95% of individual I/O latencies within a 10% error margin, outperforming existing simulators and ML models, which achieve only 6%–37% accuracy, while also providing 4×–255× speedups in prediction latency.
draft: false
url_pdf: https://ieeexplore.ieee.org/document/10171430
featured: false
tags:
  - DDIO
  - Datacenter
  - Last-Level Cache
  - I/O
  - Storage
  - Network
  - CPU
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: ""
date: 2025-06-27T05:39:24.608Z
---
