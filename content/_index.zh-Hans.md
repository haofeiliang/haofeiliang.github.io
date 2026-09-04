+++
title = "主页"

[extra]
header = { title = "你好，我是梁浩飞", img = "img/profile.jpg", img_alt = "梁浩飞" }
show_reading_time = false
+++

我是[上海交通大学](https://www.sjtu.edu.cn/)计算机科学与技术专业的工程博士研究生，导师是郁昱教授。

我的研究方向是**全同态加密（FHE）**，尤其关注 TFHE 系列方案。我的工作围绕基于 LWE/RLWE 的 FHE，涵盖隐私保护协议设计、噪声分析与参数选择，以及使用 Rust 开发和优化高性能 FHE 实现；目前正在为 [**primus-fhe**](/zh-Hans/projects/primus-fhe/) 开发基于开源 FFT 后端的 Fourier 域计算路径。

我有 3 篇论文发表于 USENIX Security 2026，另有 1 篇被 ACM CCS 2026 接收，其中 2 篇为第一作者；同时担任多个开源实现的主要开发者。

## 研究亮点

- [**InstantOMR**](/zh-Hans/projects/instantomr/)——面向接收者隐私、具有低在线延迟和消息级并行性的单服务器不经意消息检索方案。
- [**Relect**](/zh-Hans/projects/relect/)——基于 Ring-LWE、无需可信设置并支持逐轮动态选举的单秘密领导人选举协议。
- [**Ajax**](/zh-Hans/projects/ajax/)——面向 FHEW 类方案的无噪声洪泛门限密钥生成与解密协议；我主要负责 FHE 部分。
- [**HasteBoots**](/zh-Hans/projects/hasteboots/)——面向 TFHE 可编程自举的专用简洁证明系统；我主要负责 FHE 部分。

## 研究软件

- [**primus-fhe**](/zh-Hans/projects/primus-fhe/)——提供可复用 TFHE/FHEW 类原语和多项式运算后端的高性能 Rust 库。
- [**Lattice Estimator Web/API**](/zh-Hans/projects/lattice-estimator/)——将我用于 FHE 参数具体安全性评估的 Python 工作流封装为可通过 Docker 部署的界面。

[查看全部论文](/zh-Hans/publications/) · [浏览研究软件](/zh-Hans/projects/) · [下载我的简历](/zh-Hans/cv/)
