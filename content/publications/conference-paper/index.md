---
title: 'The Impact of Quantum-Safe Cryptography (QSC) on Website Response'

authors:
  - admin

date: '2025-08-14T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-14T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Cyber Security and Intelligent Systems, Lecture Notes in Networks and Systems, vol 1425*
publication_short: In *LNNS 1425*

abstract: |
  Modern web traffic relies on 2048-bit RSA encryption to secure our data in transit. Rapid advances in Quantum Computing pose a grave challenge by allowing hackers to break this encryption in hours. In August of 2024, the National Institute of Standards and Technology published Quantum-Safe Cryptography (QSC) standards, including CRYSTALS-Kyber for general encryption and CRYSTALS-Dilithium, FALCON, and SPHINCS+ for digital signatures. Despite this proactive approach, the slow adoption of encryption protocols remains a concern, leaving a significant portion of data vulnerable to interception. In this context, this study aims to evaluate the impact of NIST’s Quantum-Resistant Cryptographic Algorithms on website response times, particularly focusing on SSL handshake time and total download time under varying network conditions. By assessing the performance of these algorithms, this research seeks to provide empirical evidence and a reusable framework for validating the efficacy of QSC in real-world scenarios. It was found that the QSC algorithms outperformed the classical algorithm under normal and congested network conditions. There was also found to be an improvement in the total download time for larger file sizes, and a better performance by QSC under higher latency and packet loss conditions. Therefore, this study recommends that websites switch to QSC when the standards are ratified. These insights are crucial for accelerating the adoption of QSC and ensuring the security of data in the face of quantum computing threats. A limitation of this study is that real-world network environments may exhibit additional complexities and variations not captured in this test environment, which may affect the generalizability of the findings.

# Summary. An optional shortened abstract.
summary: Research exploring how Quantum-Safe Cryptography affects website performance, presented in Springer LNNS 1425 conference proceedings.

tags:
  - Quantum-Safe Cryptography
  - Cybersecurity
  - Website Performance

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-92608-2_14

# Custom links
links:
  - type: publication
    url: https://link.springer.com/chapter/10.1007/978-3-031-92608-2_14
  - type: pdf
    url: https://arxiv.org/pdf/2411.05024v1
  - type: preprint
    provider: arxiv
    id: 2411.05024v1
  - type: dataset
    url: ""
  - type: slides
    url: ""
  - type: video
    url: ""
  - type: source
    url: ""

# Featured image
image:
  caption: 'Image credit: [**Springer**](https://link.springer.com/)'
  focal_point: ''
  preview_only: false

projects: []

slides: ""
---
