---
publication_types:
  - "1"
authors:
  - admin
  - Won Woo Ro
publication_short: ""
abstract: >-
  Performance of dynamic optimization system is strongly affected by the region
  it selects to optimize. Larger region has more opportunities to exploit the
  potential of optimization techniques, but it also has the risk of flushing and
  re-execution of correct-path instructions caused by the internal
  mis-speculations. To address this problem, we propose a method for
  constructing resilient regions by constructing them across multiple branches
  only when the branches exhibit a biased behavior. To minimize the re-execution
  of correct-path instructions as well as to provide meaningful performance
  gain, we also propose to monitor the behavior of dynamic branches and
  adaptively adjust the merging threshold with respect to application phase
  changes.

  We first analyze the divergence pattern of dynamic branches, and then describe proposed region construction techniques (static and dynamic methods). Our evaluation results show that the proposed design with dynamic adjustment scheme shows the best coverage (over 85%) with negligible performance degradation.
draft: false
url_pdf: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: Constructing Resilient Region in Dynamic Optimization Systems via Dynamic
  Adjustment of Bias Thresholds
doi: ""
publication: IEEE International Conference On Consumer Electronics Asia (ICCE-ASIA)
featured: false
tags:
  - CPU
  - Microarchitecture
  - Dynamic Optimization
  - Branch
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: CASINO core microarchitecture overview
date: 2018-06-01T00:00:00.540Z
url_slides: ""
url_poster: ""
url_code: ""
---
