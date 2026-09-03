+++
title = "Ajax"
description = "面向 FHEW 类方案的无噪声洪泛门限密钥生成与解密协议"
weight = 5
template = "info-page.html"

[taxonomies]
tags = ["FHE", "门限全同态加密"]

[extra]
show_reading_time = false
+++

门限 FHE 将秘密密钥分布在多个参与方之间，因此需要围绕底层 FHE 方案设计门限密钥生成与解密协议。

**Ajax** 面向 FHEW 类密码体制设计上述协议。其门限解密采用基于跨环随机双份额的 mask-then-open 技术，在保留较小 FHE 参数的同时避免噪声洪泛；门限密钥生成则降低了噪声随参与方数量增长的幅度。

### 个人贡献

- 主要负责 FHE 部分的实现与性能优化。
- MPC 部分由其他合作者完成。
- 对应论文发表于 USENIX Security 2026。

### 相关资源

[源代码](https://github.com/primus-labs/Ajax)

[USENIX Security '26](https://www.usenix.org/conference/usenixsecurity26/presentation/hu-zhenkai)

[IACR ePrint 2025/1834](https://eprint.iacr.org/2025/1834)
