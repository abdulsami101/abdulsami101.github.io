---
title: "Unified Diffusion Model with Multi-Scale Style Infusion"
excerpt: "A single-phase diffusion framework for font generation, combining multi-scale style injection with structure-aware losses across Korean, Chinese, and Latin scripts."
collection: portfolio
permalink: /portfolio/unified-diffusion-style-infusion/
thumbnail: /images/korean.PNG
---

This project develops a diffusion-based font generation framework that removes the limitations of two-stage pipelines by unifying training into a single phase. The model learns style representation and structural generation simultaneously, producing more coherent synthesis at lower training cost.

**Key contributions**

- Multi-scale style infusion: style vectors injected at the encoder, bottleneck, and decoder stages of the U-Net.
- Sobel-based structural consistency loss enforcing stroke-level fidelity during denoising.
- CLIP-based style loss for perceptual alignment between reference and generated glyphs.
- Korean, Chinese, and Latin script generation from minimal reference samples.

Research ongoing; code and an extended journal manuscript are in preparation.
