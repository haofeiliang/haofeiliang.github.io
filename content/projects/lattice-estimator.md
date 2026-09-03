+++
title = "Lattice Estimator Web/API"
description = "A reusable workflow for concrete security evaluation of FHE parameters"
weight = 4
template = "info-page.html"

[taxonomies]
tags = ["Lattice Cryptography", "Security Estimation", "FHE Parameters"]

[extra]
show_reading_time = false
+++

The **Lattice Estimator Web/API** project grew out of a practical need in my FHE work: evaluating whether candidate parameter sets provide sufficient concrete security.

Before building the Web interface, I wrote Python scripts that directly invoked the SageMath-based [`malb/lattice-estimator`](https://github.com/malb/lattice-estimator). This involved translating FHE parameters into estimator inputs, running the available attack estimates, and comparing the resulting security levels. That estimator workflow and parameter-security evaluation are the parts most representative of my own technical experience.

I later used AI-assisted development to package the workflow as a Docker-deployable Web/API tool. My direct technical work focuses on mapping FHE parameters to estimator inputs, invoking attack estimates, comparing results, and validating outputs; the Web/API layer makes the workflow easier to reproduce and use.

### Resources

[Web/orchestration source](https://github.com/haofeiliang/lattice-estimator-web)

[SageMath API source](https://github.com/haofeiliang/lattice-estimator-api)

[Upstream lattice-estimator](https://github.com/malb/lattice-estimator)
