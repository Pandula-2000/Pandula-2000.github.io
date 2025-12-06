---
title: " From Samples to Functions: Implicit Neural Representations for Continuous Modeling"
collection: publications
category: conferences
permalink: /publication/2025-BandRC
excerpt: 'Accepted at ICIIS 2025'
date: 2025
venue: 'ICIIS'
# paperurl: ''

---

In the domain of signal representation, Implicit Neural Representations (INR) are emerging as a new trend. INRs offer a compact, memory-efficient, and scalable way to represent signals. Essentially, INRs are a class of functions that can learn a continuous representation from a given discrete signal. An INR can be formulated by building a multi-layer perceptron network equipped with specially tailored activation functions. It is extensively shown that INR networks excel at solving complex inverse problems. This study presents a comprehensive analysis of current INR methods with a detailed performance comparison against classical methods for representation tasks and inverse problems. For image denoising, SOTA INRs are able to retain structural information more effectively (with +0.35 SSIM over best classical methods) though PSNR of classical methods are higher. Also showcased is the storage efficiency for INRs in 3D reconstruction (with INRs occupying approximately 1\% of storage compared to classical representations). However, for representations with lower complexity, classical methods still remain superior (with +12.44 dB PSNR over SOTA INRs for image representation and +2.47 dB for 6X image super-resolution).