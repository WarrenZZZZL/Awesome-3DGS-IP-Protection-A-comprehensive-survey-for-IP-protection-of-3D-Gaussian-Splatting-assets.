# Awesome-3DGS-IP-Protection-A-comprehensive-survey-for-IP-protection-of-3D-Gaussian-Splatting-assets.
A comprehensive survey on intellectual property protection for 3D Gaussian Splatting assets, presenting a unified taxonomy, embedding-space analysis, robustness characterization, and future roadmap, covering watermarking, steganography, tampering localization, and editing safeguards.




# IP Protection for 3D Gaussian Splatting

> **A curated and structured hub for intellectual property protection in 3D Gaussian Splatting (3DGS).**  
> This repository organizes watermarking, steganography, tampering localization, and editing safeguard methods under a unified framework.
> First survey to summarize the 3DGS IP protection **Toward Robust Intellectual Property Protection for 3D Gaussian Splatting Assets and Beyond**

---

## 🔍 What is 3DGS IP Protection?

3D Gaussian Splatting (3DGS) has become a dominant paradigm for real-time novel view synthesis and AI-generated 3D content.  
However, its explicit and editable parameterization makes 3DGS assets highly vulnerable to:

- Unauthorized copying and redistribution  
- Hidden data leakage  
- Malicious generative AI editing  

This repository provides a structured overview of **all known IP protection methods for 3DGS**.

---

## 🧭 Unified Framework

<img width="715" height="593" alt="Image" src="https://github.com/user-attachments/assets/8903040b-3345-4ba3-92d7-9b8628d7418b" />


**3DGS IP protection methods can be categorized into two paradigms:**

| Category | Purpose |
|---------|---------|
| **Passive Protection** | Post-hoc ownership verification, covert communication, tampering detection |
| **Active Protection** | Proactively preventing unauthorized AI editing |

---

## 🧩 Protection Taxonomy

<img width="1040" height="633" alt="Image" src="https://github.com/user-attachments/assets/df6efbae-909f-438c-a113-118066eea994" />


Each method is characterized along three orthogonal dimensions:

| Dimension | Description |
|----------|-------------|
| **Micro** | Which Gaussian attributes are used for embedding (SH, geometry, hybrid) |
| **Macro** | Which Gaussians are modified (global / local / frequency-guided) |
| **Pipeline** | When perturbations are injected (post-hoc / training / in-generation) |

These dimensions define the **embedding space of Gaussian-represented perturbations**.

---




# IP Protection Methods for 3D Gaussian Splatting

## Watermarking (Passive)

| Abbreviation | Full Paper Title | GitHub Link |
|--------------|------------------|-------------|
| GaussianMarker | GaussianMarker: Uncertainty-Aware Copyright Protection of 3D Gaussian Splatting | https://github.com/kevinhuangxf/GaussianMarker |
| WATER-GS | WATER-GS: Toward Copyright Protection for 3D Gaussian Splatting via Universal Watermarking | - |
| 3D-GSW | 3D-GSW: 3D Gaussian Splatting for Robust Watermarking | https://github.com/kuai-lab/cvpr25_3D-GSW |
| GuardSplat | GuardSplat: Efficient and Robust Watermarking for 3D Gaussian Splatting | https://github.com/NarcissusEx/GuardSplat |
| MarkSplatter | MarkSplatter: Generalizable Watermarking for 3D Gaussian Splatting Model via Splatter Image Structure | - |
| MantleMark | MantleMark: Migrating Watermarks from Multi-View Images to Radiance Fields via Frequency Modulation | - |
| NGS-Marker | NGS-Marker: Neural Gaussian Splatting Marker for Robust Watermarking | - |
| X-SG²S | X-SG²S: Safe and Generalizable Gaussian Splatting with X-dimensional Watermarks | - |
| CompMarkGS | CompMarkGS: Compression-Aware Watermarking for 3D Gaussian Splatting | - |
| GaussianSeal | GaussianSeal: Rooting Adaptive Watermarks for 3D Gaussian Generation Model | - |
| GS-Marker | GS-Marker: Generalizable and Robust Watermarking for 3D Gaussian Splatting | - |
| RDSplat | RDSplat: Robust and Diverse Watermarking for 3D Gaussian Splatting | - |

## Steganography (Passive)

| Abbreviation | Full Paper Title | GitHub Link |
|--------------|------------------|-------------|
| GS-Hider | GS-Hider: Hiding Messages into 3D Gaussian Splatting | https://github.com/xuanyuzhang21/GS-Hider |
| StegaGaussian | StegaGaussian: High-fidelity Steganography for 3D Gaussian Splatting based on Frequency Decomposition | - |
| KeySS | KeySS: All You Need is a Key - Secure Steganography for 3D Gaussian Splatting | - |
| Hide A Bit | Hide A Bit: Hiding Bits in 3D Gaussian Splatting | - |
| InstantSplamp | InstantSplamp: Instant Splatting with Steganographic Embedding | - |
| SecureGS | SecureGS: Boosting the Security and Fidelity of 3D Gaussian Splatting Steganography | - |
| ConcealGS | ConcealGS: Concealing Information in 3D Gaussian Splatting | - |
| Splats in Splats | Splats in Splats: Embedding Invisible 3D Watermark within Gaussian Splatting | - |

## Tampering Localization (Passive)

| Abbreviation | Full Paper Title | GitHub Link |
|--------------|------------------|-------------|
| GS-Checker | GS-Checker: Tampering Localization for 3D Gaussian Splatting | - |

## Editing Safeguard (Active)

| Abbreviation | Full Paper Title | GitHub Link |
|--------------|------------------|-------------|
| DEGauss | DEGauss: Defending Against Malicious 3D Editing for Gaussian Splatting | - |
| AdLift | AdLift: Adversarial Lifting for 3D Gaussian Splatting | - |

---
**Note:**
- "-" indicates that no public GitHub repository was found
- Some papers may have project pages but have not open-sourced their code




