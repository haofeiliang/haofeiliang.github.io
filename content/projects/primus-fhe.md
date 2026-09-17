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

Development is maintained in my repository and progressively integrated upstream into Primus Labs. The implementation covers a unified FHE core and both NTT and open-source FFT-based Fourier-domain computation paths.

- Lead developer and maintainer
- Rust implementations of reusable TFHE/FHEW-style core operations
- NTT and open-source FFT-based Fourier-domain arithmetic backends
- Performance profiling, parallel optimization, and correctness and noise validation

### Resources

[Current development branch](https://github.com/haofeiliang/primus-fhe/tree/feat/fhe_core)

[Upstream repository](https://github.com/primus-labs/primus-fhe)
