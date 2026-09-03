+++
title = "Relect"
description = "Ring-LWE-based single-secret leader election without trusted setup"
weight = 3
template = "info-page.html"

[taxonomies]
tags = ["FHE", "Leader Election"]

[extra]
show_reading_time = false
+++

In single-secret leader election (SSLE), all parties jointly and obliviously elect one leader; only the selected leader learns the outcome unless they choose to reveal it.

**Relect** is an efficient SSLE protocol based on the Ring-LWE assumption. It uses the algebraic structure of threshold FHE together with tailored homomorphic circuits. Compared with prior concretely implemented work, it removes the trusted-setup assumption, supports dynamic leader selection in every round, and reduces local FHE computation and communication costs.

### Contribution

- First author of the corresponding ACM CCS 2026 paper.
- Lead developer of the open-source implementation and experimental evaluation.
- Protocol design, tailored FHE circuits, implementation, and performance evaluation.

### Resources

[Source code](https://github.com/haofeiliang/new-ssle)

[IACR ePrint 2026/1619](https://eprint.iacr.org/2026/1619)

[ACM CCS 2026 accepted papers](https://www.sigsac.org/ccs/CCS2026/program/accepted-papers.html)
