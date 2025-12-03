---
title: "A text-information-controlled diffusion model for multimodal whole-body PET synthesis from MRI"
collection: publications
category: conferences
permalink: /publication/2025-10-14-conference-paper
excerpt: 'This paper is about sythensis PET from T1w MRI using text and image controlled diffusion model'
date: 2025-10-17
venue: 'Fifth International Conference on Biomedicine and Bioinformatics Engineering'
paperurl: ''
citation: 'Jiang Y, Jin Y, Chen Q, et al. A text-information-controlled diffusion model for multimodal whole-body PET synthesis from MRI[C]//Fifth International Conference on Biomedicine and Bioinformatics Engineering (ICBBE 2025). SPIE, 2025, 13971: 102-107.'
---


Positron Emission Tomography (PET) is crucial for staging and monitoring systemic diseases, but its application is often constrained by high costs, radiation exposure, and limited availability. Synthesizing PET images from routinely acquired Magnetic Resonance Imaging (MRI) presents a promising alternative. This study introduces a flexible framework for synthesizing whole-body PET images of three different tracer(¹⁸F-Fluorodeoxyglucose (FDG), 68Ga-Prostate-Specific Membrane Antigen (PSMA), and 68Ga-DOTATATE) directly from MRI using a single generative model. Our method enhances a pre-trained Stable Diffusion Model by incorporating two critical components: a control module that conditions on MRI for precise anatomical alignment, and a fine-tuned text encoder to specify the desired PET tracer. This dual-conditioning architecture enables a single model to synthesize multiple, high-fidelity PET modalities with strict structural control. Quantitative and qualitative evaluations demonstrate that our method outperforms conventional image-to-image translation baselines in terms of image fidelity and realism. Bland-Altman analysis revealed low bias for all three tracers. Our results validate that a text-conditioned diffusion model can serve as a powerful and scalable tool for high-fidelity, multi-tracer PET synthesis.
