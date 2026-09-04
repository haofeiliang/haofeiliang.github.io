+++
title = "Home"

[extra]
header = { title = "Hi, I'm Haofei Liang", img = "img/profile.jpg", img_alt = "Haofei Liang" }
show_reading_time = false
+++

I am a doctoral candidate in Computer Science and Technology (Doctor of Engineering) at [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/), advised by Prof. Yu Yu.

My research focuses on **fully homomorphic encryption (FHE)**, particularly the TFHE scheme family. My work centers on LWE/RLWE-based FHE, spanning privacy-preserving protocol design, noise analysis and parameter selection, and the development and optimization of high-performance Rust implementations. I am currently developing a Fourier-domain computation path for [**primus-fhe**](/projects/primus-fhe/) using open-source FFT backends.

I have three papers published at USENIX Security 2026 and one accepted at ACM CCS 2026, including two first-authored papers. I am also a lead or primary developer of their open-source implementations.

## Research highlights

- [**InstantOMR**](/projects/instantomr/) — single-server oblivious message retrieval with low online latency and message-level parallelism.
- [**Relect**](/projects/relect/) — Ring-LWE-based single-secret leader election without trusted setup and with dynamic per-round selection.
- [**Ajax**](/projects/ajax/) — threshold key-generation and decryption for FHEW-like schemes without noise flooding; I primarily implemented the FHE component.
- [**HasteBoots**](/projects/hasteboots/) — succinct arguments tailored to TFHE programmable bootstrapping; I primarily handled the FHE component.

## Research software

- [**primus-fhe**](/projects/primus-fhe/) — a high-performance Rust library for reusable TFHE/FHEW-style primitives and polynomial-arithmetic backends.
- [**Lattice Estimator Web/API**](/projects/lattice-estimator/) — a Docker-deployable interface around the Python workflow I use for concrete security evaluation of FHE parameters.

[View all publications](/publications/) · [Explore research software](/projects/) · [Download my CV](/cv/)
