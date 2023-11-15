---
title: A Convertible Neural Processor Supporting Adaptive Quantization for
  Real-Time Neural Networks
publication_types:
  - "2"
authors:
  - Hongju Kal
  - Hyoseong Choi
  - admin
  - Junsung Yang
  - Won Woo Ro
publication: Journal of Systems Architecture
abstract: This paper presents Stimpack, a responsive approach toward adaptive
  neural processing unit (NPU), aiming to satisfy service-level objectives
  (SLOs) under highly massive loads of neural network (NN) inference. Initially,
  Stimpack operates in a base-mode processing and computes NNs similarly to a
  conventional NPU accelerator. During base-mode processing, if SLO violation is
  likely to occur soon, it changes the operation mode to a burst-mode
  processing. In the burst-mode processing, Stimpack computes quantized networks
  instead of the original ones, enabling computational throughput to be scaled
  up to two times higher than the base-mode processing. This switchable
  processing is facilitated by three hardware/software schemes. First, a
  reconfigurable core is adopted to support two different precisions and boost
  processing throughput for avoiding SLO violations. As computation resources
  can be shared between the two operation modes, the area overhead of a
  reconfigurable core is negligible. The second is an on-chip quantization unit
  that mitigates the data transfer overhead incurred by mode changing. It
  quantizes parameters stored in on-chip memory on the fly, instead of bringing
  quantized parameters from off-chip memory. Third, Stimpack leverages a
  scheduler that determines mode switching based on the amount of workloads in
  the server. By monitoring ongoing and queued requests of NPU, the scheduler
  conservatively activates burst-mode processing to minimize accuracy loss. Our
  analysis shows that, compared to a state-of-the-art NPU, Stimpack achieves
  48.4% speedup and allows a 41.4% large load on average while satisfying SLO
  and near-ideal accuracy.
draft: false
url_pdf: https://www.sciencedirect.com/science/article/pii/S1383762123002047
doi: ""
featured: false
tags:
  - Processing-in-Memory
  - Deep Learning
image:
  filename: ""
  focal_point: Smart
  preview_only: false
  caption: ""
summary: ""
date: 2023-11-15T20:35:24.780Z
---
