---
publication_types:
  - "1"
authors:
  - Haneul Park
  - Jiaqi Lou
  - Sangjin Lee
  - Yifan Yuan
  - KyoungSoo Park
  - Yongseok Son
  - admin
  - Nam Sung Kim
publication: ACM/IEEE International Symposium on Computer Architecture (ISCA)
abstract: "In modern server CPUs, the Last-Level Cache (LLC) serves not
only as a victim cache for higher-level private caches but also as a
buffer for low-latency DMA transfers between CPU cores and I/O
devices through Direct Cache Access (DCA). However, prior work
has shown that high-bandwidth network-I/O devices can rapidly
flood the LLC with packets, often causing significant contention
with co-running workloads. One step further, this work explores
hidden microarchitectural properties of the Intel Xeon CPUs, uncovering two previously unrecognized LLC contentions triggered
by emerging high-bandwidth I/O devices. Specifically, (C1) DMA-
written cache lines in LLC ways designated for DCA (referred to
as DCA ways) are migrated to certain LLC ways (denoted as inclusive ways) when accessed by CPU cores, unexpectedly contending
with non-I/O cache lines within the inclusive ways. In addition,
(C2) high-bandwidth storage-I/O devices, which are increasingly
common in datacenter servers, benefit little from DCA while contending with (latency-sensitive) network-I/O devices within DCA
ways. To this end, we present A4, a runtime LLC management
framework designed to alleviate both (C1) and (C2) among diverse
co-running workloads, using a hidden knob and other hardware
features implemented in those CPUs. Additionally, we demonstrate
that A4 can also alleviate other previously known network-I/O-driven LLC contentions. Overall, it improves the performance of
latency-sensitive, high-priority workloads by 51% without notably
compromising that of low-priority workloads."
draft: false
url_pdf: "https://dl.acm.org/doi/full/10.1145/3695053.3731114"
featured: true
summary: "This work uncovers two previously unknown sources of Last-Level Cache (LLC) contention in Intel Xeon CPUs caused by high-bandwidth I/O devices and proposes A4, a runtime LLC management framework that mitigates these issues. A4 improves performance for latency-sensitive workloads by 51% without significantly affecting low-priority workloads."
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
url_tutorial: ""
title: "A4: Microarchitecture-Aware LLC Management for Datacenter Servers with Emerging I/O Devices"
tags:
  - CPU
  - Microarchitecture
  - Last-level cache
  - Data direct I/O
  - Datacenter
image:
  filename: "a4.png"
  focal_point: SMART
  preview_only: false
  caption: 
date: 2025-04-08T07:42:18.616Z
url_slides: ""
url_poster: ""
url_code: ""
---
