+++
title = "Ajax"
description = "Threshold key generation and decryption for FHEW-like schemes without noise flooding"
weight = 5
template = "info-page.html"

[taxonomies]
tags = ["FHE", "Threshold FHE"]

[extra]
show_reading_time = false
+++

Threshold FHE distributes the secret key across multiple parties and therefore requires threshold key-generation and decryption protocols around the underlying FHE scheme.

**Ajax** designs these protocols for FHEW-like cryptosystems. Its threshold decryption uses a mask-then-open technique based on random double sharings over different rings, avoiding noise flooding while retaining small FHE parameters. Its threshold key generation also reduces how noise grows with the number of parties.

### Contribution

- Primarily responsible for implementing and optimizing the FHE component.
- The MPC component was developed by other collaborators.
- Corresponding paper at USENIX Security 2026.

### Resources

[Source code](https://github.com/primus-labs/Ajax)

[USENIX Security '26](https://www.usenix.org/conference/usenixsecurity26/presentation/hu-zhenkai)

[IACR ePrint 2025/1834](https://eprint.iacr.org/2025/1834)
