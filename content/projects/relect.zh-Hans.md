+++
title = "Relect"
description = "基于 Ring-LWE、无需可信设置的单秘密领导人选举协议"
weight = 3
template = "info-page.html"

[taxonomies]
tags = ["FHE", "领导人选举"]

[extra]
show_reading_time = false
+++

在单秘密领导人选举（SSLE）中，各方共同且不经意地选出一名领导者；除非当选者主动公开，其他参与方无法获知其身份。

**Relect** 是一种基于 Ring-LWE 假设的高效 SSLE 协议。它利用门限 FHE 的代数结构并设计专用同态电路；与此前具有具体实现的工作相比，Relect 无需可信设置，支持每轮动态选择领导者，并降低本地 FHE 计算与通信开销。

### 个人贡献

- ACM CCS 2026 对应论文的第一作者。
- 开源实现和实验评估的主要开发者。
- 协议设计、专用 FHE 电路、实现与性能评估。

### 相关资源

[源代码](https://github.com/haofeiliang/new-ssle)

[IACR ePrint 2026/1619](https://eprint.iacr.org/2026/1619)

[ACM CCS 2026 接收论文列表](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)
