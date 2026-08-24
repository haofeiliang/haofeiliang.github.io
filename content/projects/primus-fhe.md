+++
title = "primus-fhe"
description = "High-performance Rust library for TFHE research and implementations"
weight = 1
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "NTT"]

[extra]
show_reading_time = false
+++

**primus-fhe** is the main open-source FHE implementation library for my research projects. Written in Rust, it provides high-performance TFHE primitives, including number-theoretic-transform-based implementations, as reusable building blocks for FHE schemes and privacy-preserving protocols.

Recent project-specific FHE implementations that were developed in **primus** are currently being migrated back into **primus-fhe**. This consolidation keeps common cryptographic primitives, parameter sets, and performance optimizations in one codebase while allowing each research project to retain its protocol-specific logic.

- Lead developer and maintainer
- High-performance NTT-based TFHE implementation
- Shared FHE backend for current and future research projects
- Ongoing consolidation of reusable implementations from primus

### Resources

[Source code](https://github.com/primus-labs/primus-fhe)
