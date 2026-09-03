+++
title = "primus-fhe"
description = "High-performance Rust library for TFHE research and implementations"
weight = 1
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "Rust"]

[extra]
show_reading_time = false
+++

**primus-fhe** is the main open-source FHE implementation library for my research projects. Written in Rust, it provides reusable TFHE/FHEW-style core operations, ciphertext transformations, and polynomial-arithmetic backends for FHE schemes and privacy-preserving protocols.

The current development branch introduces a more unified FHE core and a Fourier-domain computation path using open-source FFT libraries alongside the existing NTT path. This work is being developed in my [`feat/fhe_core`](https://github.com/haofeiliang/primus-fhe/tree/feat/fhe_core) branch and is intended for consolidation into the upstream **primus-fhe** repository.

- Lead developer and maintainer
- Rust implementations of reusable TFHE/FHEW-style core operations
- Existing NTT path and an in-progress Fourier-domain backend
- Performance profiling, parallel optimization, and correctness and noise validation

### Resources

[Current development branch](https://github.com/haofeiliang/primus-fhe/tree/feat/fhe_core)

[Upstream repository](https://github.com/primus-labs/primus-fhe)
