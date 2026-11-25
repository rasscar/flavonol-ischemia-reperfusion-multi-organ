# Mechanistic Signaling Models: Flavonol Intervention in Multi-Organ Ischemia-Reperfusion Injury

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Diagram Engine](https://img.shields.io/badge/Diagram-Mermaid.js-blue.svg)](https://mermaid.js.org/)

## Overview
This repository hosts reproducible, vector-based mechanistic pathway models accompanying the scoping review:
> **Yuliani, N. S., Lazuardi, M., & Hestianah, E. P.** *Flavonol Intervention in Ischemia-Reperfusion-Induced Multi-Organ Dysfunction: Mechanistic Insights into Nrf2 Signaling, NF-κB Regulation, and Controlled Cell Death Pathways.* Faculty of Veterinary Medicine, Universitas Airlangga.

## Included Pathway Models
1. **`fig3_mitochondrial_protection.mmd`**: Corrected mitochondrial bioenergetics and intrinsic apoptosis inhibition pathway mediated by Morin and Quercetin (`mt-KATP` activation, mild membrane depolarization, `mPTP` closure, `Bcl-2/Bax` modulation, and caspase cascade arrest).
2. **`fig4_convergent_signaling_network.mmd`**: Integrated multi-target convergence model across 34 preclinical studies covering Keap1/Nrf2/HO-1, TLR4/IKKβ/NF-κB, Ferroptosis (`ATF3/SLC7A11/GPX4`), Pyroptosis (`Caspase-8/ASC/NLRP3/GSDMD`), Autophagy (`Bcl-2/Beclin-1`, `Nurr1/AKT/TFEB`), and Nano-DDS (`Liposomes`, `MSNs`).

## Rendering High-Resolution Figures (600 DPI / Vector SVG)
To render publication-grade vector graphics locally using `@mermaid-js/mermaid-cli`:
```bash
npm install -g @mermaid-js/mermaid-cli
bash scripts/render_publication_figures.sh
