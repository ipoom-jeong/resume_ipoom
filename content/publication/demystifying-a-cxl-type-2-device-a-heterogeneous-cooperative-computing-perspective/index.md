---
publication_types:
  - "1"
authors:
  - Houxiang Ji
  - Srikar Vanavasam
  - Yang Zhou
  - Qirong Xia
  - Jinghan Huang
  - Yifan Yuan
  - Ren Wang
  - Pekon Gupta
  - Bhushan Chitlur
  - admin
  - Nam Sung Kim
publication: IEEE/ACM International Symposium on Microarchitecture (MICRO)
abstract: CXL is the latest interconnect technology built on
PCIe, providing three protocols to facilitate three distinct types
of devices, each with unique capabilities. Among these devices, a
CXL Type-2 device has become commercially available, followed
by CXL Type-3 devices. Therefore, it is timely to understand
capabilities and characteristics of the CXL Type-2 device, as
well as explore suitable applications. In this work, first, we delve
into three key features of a CXL Type-2 device\: cache-coherent
device accelerator to host memory, device accelerator to device
memory, and host CPU to device memory accesses. Second, using
microbenchmarks, we comprehensively characterize the latency
and bandwidth of these memory accesses with a CXL Type-2
device, and then compare them with those of equivalent memory
accesses with comparable devices, such as emulated CXL Type-2,
CXL Type-3, and PCIe devices. Lastly, as applications that exploit
the unique capabilities of a CXL Type-2 device, we propose two
CXL-based Linux memory optimization features\: compressed
RAM cache for swap (zswap) and memory deduplication (ksm).
Our evaluation shows that Redis, when running with traditional
CPU-based zswap and ksm, suffers from a tail latency increase
of 4.5–10.3× compared to Redis running alone. While PCIebased zswap and ksm still experience a tail latency increase of
up to 8.1×, CXL-based zswap and ksm practically eliminate the
tail latency increase with faster and more efficient host-device
communication than PCIe-based zswap and ksm.

draft: false
url_pdf: ""
featured: false
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
url_tutorial: ""
title: "Demystifying a CXL Type-2 device: A heterogeneous cooperative computing
  perspective"
tags:
  - CPU
  - CXL
  - Memory
  - Accelerator
  - System
  - Datacenter
image:
  filename: ""
  focal_point: SMART
  preview_only: false
  caption: ""
date: 2024-11-01T01:00:18.442Z
url_slides: ""
url_poster: ""
url_code: ""
---
