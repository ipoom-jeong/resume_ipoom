---
title: "TEA-RC: Thread Context-Aware Register Cache for GPUs"
publication_types:
  - "2"
authors:
  - admin
  - Yunho Oh
  - Won Woo Ro
  - Myung Kuk Yoon
publication: "IEEE Access (Volume: 10)"
abstract: "Graphics processing units (GPUs) achieve high throughput by
  exploiting a high degree of thread-level parallelism (TLP). To support such
  high TLP, GPUs have a large-sized register file to store the context of all
  threads, consuming around 20% of total GPU energy. Several previous studies
  have attempted to minimize the energy consumption of the register file by
  implementing an emerging non-volatile memory (NVM), leveraging its higher
  density and lower leakage power over SRAMs. To amortize the cost of long
  access latency of NVM, prior work adopts a hierarchical register file
  consisting of an SRAM-based register cache and NVM-based registers where the
  register cache works as a write buffer. To get the register cache index, they
  use the partially selected bits of warp ID and register ID. This work observes
  that such an index calculation causes three types of contentions leading to
  the underutilization of the register cache: inter-warp , intra-warp , and
  false contentions. To minimize such contentions, this paper proposes a thread
  context-aware register cache (TEA-RC) in GPUs. In TEA-RC, the cache index is
  calculated considering the high correlation between the number of scheduled
  threads and the register usage of threads. The proposed design shows 28.5%
  higher performance and 9.1 percentage point lower energy consumption over the
  conventional register cache that concatenates three bits of warp ID and five
  bits of register ID to compute the cache index."
draft: false
url_pdf: https://ieeexplore.ieee.org/document/9848819
featured: false
tags:
  - GPU
  - Microarchitecture
  - Register File
  - Energy Efficiency
summary: asd
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
doi: 10.1109/ACCESS.2022.3196149
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: OverCome core microarchitecture overview
date: 2022-08-03T00:00:00.225Z
url_slides: ""
url_poster: ""
url_code: ""
---
