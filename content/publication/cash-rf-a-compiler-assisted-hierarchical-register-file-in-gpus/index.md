---
publication_types:
  - "2"
authors:
  - Yunho Oh
  - admin
  - Won Woo Ro
  - Myung Kuk Yoon
publication_short: ""
abstract: Spin-transfer torque magnetic random-access memory (STT-MRAM) is an
  emerging nonvolatile memory technology that has been received significant
  attention due to its higher density and lower leakage current over SRAM. One
  compelling use case is to employ STT-MRAM as a graphics processing unit (GPU)
  register file (RF) to reduce its massive energy consumption. One critical
  challenge is that STT-MRAM has longer access latency and higher dynamic power
  consumption than SRAM, which motivates the hierarchical RF that places a small
  SRAM-based register cache (RC) between functional units and STT-MRAM RF. The
  RC acts as the write buffer, so all the writes on the RF are first performed
  on the RC. In the presence of a conflict miss, the RC writes back the
  corresponding cache line into the RF. In this work, we observe that a large
  amount of such write-back operations are unnecessary because they include
  register values that are never used again. Leveraging this observation, we
  propose a compiler-assisted hierarchical RF in GPUs (CASH-RF) that optimizes
  STT-MRAM accesses by removing dead register values. In CASH-RF, unnecessary
  write-back operations are detected by the compiler via the last consumer
  analysis. At runtime, the corresponding RC lines are discarded after the last
  references without being updated to the RF. Compared to the baseline GPUs,
  CASH-RF removes 59.5% of write-back operations, which leads to 54.7% lower RF
  energy consumption with only 2.6% of performance degradation.
draft: false
url_pdf: https://ieeexplore.ieee.org/document/9745582
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "CASH-RF: A Compiler-Assisted Hierarchical Register File in GPUs"
doi: 10.1109/LES.2022.3163749
publication: "IEEE Embedded Systems Letters (Volume: 14, Issue: 4)"
featured: false
tags:
  - GPU
  - Microarchitecture
  - Register File
  - Energy Efficiency
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: OverCome core microarchitecture overview
date: 2022-12-31T00:00:00.919Z
url_slides: ""
url_poster: ""
url_code: ""
---
