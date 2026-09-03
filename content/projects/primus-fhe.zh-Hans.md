+++
title = "primus-fhe"
description = "面向 TFHE 研究与实现的高性能 Rust 库"
weight = 1
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "Rust"]

[extra]
show_reading_time = false
+++

**primus-fhe** 是我研究项目所使用的主要开源全同态加密实现库。它使用 Rust 编写，为全同态加密方案和隐私保护协议提供可复用的 TFHE/FHEW 类核心算子、密文变换及多项式运算后端。

当前开发分支正在统一 FHE 核心接口，并在已有 NTT 路径之外，使用开源 FFT 库开发 Fourier 域计算路径。相关工作位于我的 [`feat/fhe_core`](https://github.com/haofeiliang/primus-fhe/tree/feat/fhe_core) 分支，后续计划整合到上游 **primus-fhe** 仓库。

- 主要开发者和维护者
- 可复用 TFHE/FHEW 类核心算子的 Rust 实现
- 已有 NTT 路径和正在开发的 Fourier 域后端
- 性能剖析、并行优化以及正确性与噪声验证

### 相关资源

[当前开发分支](https://github.com/haofeiliang/primus-fhe/tree/feat/fhe_core)

[上游仓库](https://github.com/primus-labs/primus-fhe)
