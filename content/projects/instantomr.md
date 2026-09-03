+++
title = "InstantOMR"
description = "Oblivious message retrieval with low latency and optimal parallelizability"
weight = 2
template = "info-page.html"

[taxonomies]
tags = ["FHE", "TFHE", "OMR"]

[extra]
show_reading_time = false
+++

Oblivious message retrieval (OMR) protects recipient privacy in anonymous messaging systems: an untrusted server helps deliver the relevant messages without learning their intended recipient, while the recipient avoids scanning every message.

**InstantOMR** is a single-server OMR construction with a two-layer bootstrapping architecture. It combines TFHE functional bootstrapping with regular RLWE homomorphic operations and is designed around two practical goals:

- **Low latency:** recipients can retrieve messages with substantially less waiting time than prior single-server OMR constructions.
- **Optimal parallelizability:** messages can be processed independently, allowing detection to scale efficiently with the available CPU cores.

The implementation demonstrates how TFHE-based techniques can overcome the latency and parallelism limitations of BFV-based OMR designs.

I am the first author of the paper and the lead developer of its implementation.

### Resources

[Source code](https://github.com/xiangxiecrypto/tfhe-omr)

[USENIX Security '26](https://www.usenix.org/conference/usenixsecurity26/presentation/liang)

[IACR ePrint 2025/2317](https://eprint.iacr.org/2025/2317)
