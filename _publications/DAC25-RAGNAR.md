---
title: "[DAC25] RAGNAR: Exploring Volatile-Channel Vulnerabilities on RDMA NIC"
collection: publications
category: conferences
permalink: /publication/DAC25-RAGNAR
# excerpt: 'RDMA side-channel security'
date: 2025-06-22
venue: '62nd ACM/IEEE Design Automation Conference (DAC25)'

paperurl: 'http://xuyp20thu.github.io/files/DAC25-RAGNAR.pdf'
bibtexurl: 'http://xuyp20thu.github.io/files/DAC25-RAGNAR.bib'

---
With the surge in data computation, Remote Direct Memory Access (RDMA) becomes crucial to offering low-latency and high throughput communication for data centers, but it faces new security threats. This paper presents RAGNAR, a comprehensive suite of hardware-contention-based volatile-channel attacks leveraging the underexplored security vulnerabilities in RDMA hardware. Through comprehensive microbenchmark reverse engineering, we analyze RDMA NICs at multiple granularity levels and then construct covert-channel attacks, achieving 3.2x the bandwidth of state-of-the-art RDMA-targeted attacks on CX-5. We apply side-channel attacks on real-world distributed databases and disaggregated memory, where we successfully fingerprint operations and recover sensitive address data with 95.6% accuracy.