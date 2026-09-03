+++
title = "Lattice Estimator Web/API"
description = "面向 FHE 参数具体安全性评估的可复用工作流"
weight = 4
template = "info-page.html"

[taxonomies]
tags = ["格密码", "安全性估计", "FHE 参数"]

[extra]
show_reading_time = false
+++

**Lattice Estimator Web/API** 源于我在 FHE 工作中的实际需求：评估候选参数是否具有足够的具体安全强度。

在制作 Web 界面之前，我自行编写 Python 脚本，直接调用基于 SageMath 的 [`malb/lattice-estimator`](https://github.com/malb/lattice-estimator)。这项工作包括把 FHE 参数转换为 estimator 输入、运行已有攻击估计，并比较输出的安全强度。Estimator 的使用流程和参数安全性评估，是该项目中最能代表我个人技术经验的部分。

在此基础上，我借助 AI 辅助开发，将评估流程封装为可通过 Docker 部署的 Web/API 工具。我的主要技术工作集中在参数到 estimator 输入的映射、攻击估计调用、结果比较与验证；Web/API 层主要用于提高流程的可复现性和易用性。

### 相关资源

[Web/任务编排仓库](https://github.com/haofeiliang/lattice-estimator-web)

[SageMath API 仓库](https://github.com/haofeiliang/lattice-estimator-api)

[上游 lattice-estimator](https://github.com/malb/lattice-estimator)
