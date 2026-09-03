+++
title = "HasteBoots"
description = "Succinct arguments tailored to TFHE programmable bootstrapping"
weight = 6
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "Zero-Knowledge Proofs"]

[extra]
show_reading_time = false
+++

**HasteBoots** is a succinct argument tailored to **TFHE programmable bootstrapping**, one of the most computationally intensive FHE operations. It uses protocols for arithmetic over quotient rings to reduce proof generation to seconds and supports batching multiple TFHE evaluations and bootstrappings.

### Contribution

- Primarily responsible for the FHE component and its implementation.
- The zero-knowledge proof component was developed by other collaborators.
- Corresponding paper at USENIX Security 2026.

### Resources

[Source code](https://github.com/f7ed/HasteBoots)

[USENIX Security '26](https://www.usenix.org/conference/usenixsecurity26/presentation/liu-fengrun)

[IACR ePrint 2025/261](https://eprint.iacr.org/2025/261)
