---
title: "SalFuseFormer: A Saliency-Guided Fusion Transformer Framework for Clinically Motivated Multi-Modal Medical Image Fusion"
collection: publications
category: manuscripts
permalink: /publication/2026-10-19-salfuseformer
excerpt: "A training-free, saliency-guided fusion framework that preserves the diagnostic false-colour encoding of PET and SPECT in transformer-based medical image fusion, validated on the Harvard Whole Brain Atlas and the ADNI-3 cohort."
date: 2026-10-22
venue: "Biomedical Signal Processing and Control, 131, 111701"
paperurl: "https://doi.org/10.1016/j.bspc.2026.111701"
citation: "Dhar, E., Lepcha, D. C., Ali, A., Mallik, S., Gaur, L., Syed Abdul, S. (2027). SalFuseFormer: A Saliency-Guided Fusion Transformer Framework for Clinically Motivated Multi-Modal Medical Image Fusion. Biomedical Signal Processing and Control, 131, 111701."
---

Existing transformer-based fusion methods achieve strong structural fidelity but do not explicitly preserve the functional colour encoding of PET and SPECT, where chrominance carries diagnostic meaning. SalFuseFormer adds two training-free inference-time modules to a domain-fine-tuned transformer backbone: saliency-masked edge injection, which sharpens MRI anatomical boundaries in low-activity regions, and adaptive chrominance fusion, which preserves functional false-colour in metabolically active hotspots. Both are governed by a single HSV-based functional activity saliency map and add no learnable parameters.

[Paper](https://www.sciencedirect.com/science/article/pii/S1746809426022597) · [DOI](https://doi.org/10.1016/j.bspc.2026.111701) · [Code](https://github.com/dawachyophel/SalFuseFormer)