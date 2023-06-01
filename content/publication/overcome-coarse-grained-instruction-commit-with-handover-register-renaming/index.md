---
publication_types:
  - "2"
authors:
  - admin
  - Changmin Lee
  - Keunsoo Kim
  - and Won Woo Ro
publication_short: ""
abstract: "Coarse-grained instruction commit mechanisms enabled the effective
  size of the instruction window to be as large as possible by committing a
  group of instructions atomically. Within a group, the reorder buffer (ROB) and
  physical registerfile (PRF) entries are conservatively managed, and thus the
  instruction window can handle more in-flight instructions beyond the hardware
  limit. However, previous approaches have suffered from high storage
  requirements for managing group information and unbalanced lifetime of
  instruction window resources, i.e., the ROB and PRF. In this paper, we propose
  an OverCome microarchitecture based on a history-based approach to address
  these problems. First, OverCome retains the conservative allocation of the ROB
  regardless of the group size limit, thereby providing high scalability.
  Second, it handles the information of numerous groups with a low storage cost.
  These two techniques achieve a significant reduction in the pressure on the
  ROB; thus, a new bottleneck arises: the pressure on the PRF. To address this
  issue, we propose a novel register renaming technique to reduce the lifetime
  of physical registers to a large extent, by tightly coupling the early release
  and lazy allocation schemes. Thus, the proposed design strikes a balance
  between the ROB and PRF requirements. Detailed evaluation of the proposed
  techniques on a state-of-the-art superscalar processor shows that our
  proposals augment the effective size of the instruction window by more than
  4×, with a net overhead of less than 3 percent of the core area."
draft: false
url_pdf: https://ieeexplore.ieee.org/abstract/document/8807276
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
title: "OverCome: Coarse-Grained Instruction Commit with Handover Register Renaming"
doi: 10.1109/TC.2019.2936557
publication: "IEEE Transactions on Computers (Volume: 68, Issue: 12)"
featured: false
tags:
  - CPU
  - Microarchitecture
  - Instruction Window
  - Energy Efficiency
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: OverCome core microarchitecture overview
date: 2019-12-01T00:00:00.233Z
url_slides: ""
url_poster: ""
url_code: ""
---
