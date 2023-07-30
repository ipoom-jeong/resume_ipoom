---
publication_types:
  - "1"
authors:
  - Hyunjun Shin
  - Kyungmin Lee
  - admin
  - Jong Hyun Park
  - Won Woo Ro
publication_short: ""
abstract: >-
  GPGPU has been popular in many research fields due to its ability to execute
  massive operations concurrently. Each and every emerging GPU application shows
  different execution behavior, so it becomes very important to provide suitable
  execution environment for each application. Warp scheduling is one of the key
  factors that determine the performance of GPGPUs. Accordingly, various warp
  scheduling policies have been proposed. However, general warp scheduling
  policies target different optimization points, thereby dynamic switching of
  warp scheduler could yield extra performance gain. 


  In this work, we propose dynamic warp scheduler selection policy that dynamically selects the optimal warp

  scheduler for each GPU kernel by predicting the performances of given warp scheduling policies. We consider three policies: LRR, TLV, and GTO. Scheduler selection is performed based on multiple linear regression by monitoring architectural events dynamically. Our evaluation results show that proposed scheme improves

  performance of GPU by 3.6%, 9.8%, and 7.7%, compared to the LRR, TLV, and GTO, respectively.
draft: false
url_pdf: https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE07110631
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: Dynamic Warp Scheduler Selection Policy Using Linear Regression for GPUs
doi: ""
publication: International Conference on Electronics, Information and Communication (ICEIC)
featured: false
tags:
  - GPU
  - Microarchitecture
  - Warp Scheduling
  - Performance
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: CASINO core microarchitecture overview
date: 2017-01-01T00:00:00.759Z
url_slides: ""
url_poster: ""
url_code: ""
---
