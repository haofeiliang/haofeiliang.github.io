+++
title = "primus-fhe"
description = "面向 TFHE 研究与实现的高性能 Rust 库"
weight = 1
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "NTT"]

[extra]
show_reading_time = false
+++

**primus-fhe** 是我研究项目所使用的主要开源全同态加密实现库。它使用 Rust 编写，提供包括基于数论变换（NTT）的实现在内的高性能 TFHE 原语，可作为构建全同态加密方案和隐私保护协议的复用组件。

近期在 **primus** 中开发的项目专用全同态加密实现正在迁移回 **primus-fhe**。此次整合将通用密码学原语、参数集和性能优化集中到同一个代码库中，同时让各研究项目保留其协议专用逻辑。

- 主要开发者和维护者
- 基于 NTT 的高性能 TFHE 实现
- 当前及未来研究项目共用的全同态加密后端
- 持续整合来自 primus 的可复用实现

### 相关资源

[源代码](https://github.com/primus-labs/primus-fhe)
