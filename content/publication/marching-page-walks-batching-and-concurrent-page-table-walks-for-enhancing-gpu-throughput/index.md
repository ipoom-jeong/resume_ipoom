---
publication_types:
  - "1"
authors:
  - Jiwon Lee
  - Gun Ko
  - Myung Kuk Yoon
  - admin
  - Yunho Oh
  - Won Woo Ro
publication: IEEE International Symposium on High Performance Computer
  Architecture (HPCA)
abstract: "Virtual memory, with the support of address translation hardware, is a key technique in expanding programmability
and memory management in GPUs. However, the nature of the
GPU execution model heavily pressures its translation hardware,
particularly due to a discrepancy in the behavior of page table
walkers and thousands of concurrently running threads. In GPU
workloads, multiple threads simultaneously access a number of
pages necessitating a substantial number of translations whereas
each walker handles only a single walk request at a time. Such
a limitation significantly increases the queueing latency of walk
requests, which we observe as a major bottleneck for servicing
page table walks in GPUs. To tackle this challenge, we investigate
a design of page walkers that facilitates multiple walk requests
to be handled together in batches. Then, we make the following
observations: 1) allowing a page walker to issue beyond a single
memory request significantly improves the throughput of walkers,
and 2) GPU applications tend to concurrently access pages in
wide address ranges. By leveraging the above implications, we
propose Marching Page Walks (MPW), that effectively mitigate
the contention in GPU page table walkers. MPW scans pending
walk requests to identify ones that can be grouped together. Then,
MPW batches these requests and concurrently handles them by
issuing multiple memory instructions. Experiments show that
MPW reduces the queueing latency of page walks by 86.7% and
improves GPU performance by 55.6% over the baseline design."
draft: false
url_pdf: "https://ieeexplore.ieee.org/abstract/document/10946291"
featured: false
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
url_tutorial: ""
title: "Marching Page Walks: Batching and Concurrent Page Table Walks for
  Enhancing GPU Throughput"
tags:
  - GPGPU
  - Microarchitecture
image:
  filename: ""
  focal_point: SMART
  preview_only: false
  caption: ""
date: 2025-03-01T04:00:27.954Z
url_slides: ""
url_poster: ""
url_code: ""
---
