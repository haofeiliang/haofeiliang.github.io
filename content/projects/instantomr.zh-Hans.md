+++
title = "InstantOMR"
description = "具有低延迟和最优并行性的不经意消息检索方案"
weight = 2
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "OMR"]

[extra]
show_reading_time = false
+++

不经意消息检索（Oblivious Message Retrieval，OMR）允许资源受限的接收者将消息检测与取回工作外包出去，同时不泄露匿名消息系统或隐私区块链中的哪些消息属于自己。

**InstantOMR** 是一种混合型 OMR 构造，将 TFHE 函数自举与标准 RLWE 运算相结合，围绕两个实际目标设计：

- **低延迟：**与此前的单服务器 OMR 构造相比，接收者可以显著缩短等待消息取回的时间。
- **最优并行性：**各条消息可以独立处理，使检测过程能够随可用 CPU 核心数量高效扩展。

该实现展示了基于 TFHE 的技术如何克服基于 BFV 的 OMR 设计在延迟和并行性方面的局限。

我是论文第一作者，也是实现的主要开发者。

### 相关资源

[源代码](https://github.com/xiangxiecrypto/tfhe-omr)

[USENIX Security '26](https://www.usenix.org/conference/usenixsecurity26/presentation/liang)

[IACR ePrint 2025/2317](https://eprint.iacr.org/2025/2317)
