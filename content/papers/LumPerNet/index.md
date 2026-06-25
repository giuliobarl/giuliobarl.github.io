---
title: "Quantifying Perovskite Solar Cell Degradation via Machine Learning from Spatially Resolved Multimodal Luminescence Time Series" 
date: 2026-03-13
lastmod: 2026-03-13
tags: ["Artificial Intelligence", "Machine Learning", "Perovskite", "Photovoltaics", "Luminescence Imaging", "Degradation Diagnostics", "Efficiency Retention"]
author: ["Giulio Barletta", "Simon Ternes", "Saif Ali", "Zohair Abbas", "Chiara Ostendi", "Marialucia D'Addio", "Erica Magliano", "Pietro Asinari", "Eliodoro Chiavazzo", "Aldo Di Carlo"]
description: "This paper presents the novel LumPerNet protocol for perovskite solar cells degradation diagnostics. Preprint published in arXiv, 2025." 
summary: "This paper presents the novel LumPerNet protocol for perovskite solar cells degradation diagnostics." 
cover:
    image: "cover_figure.png"
    alt: "LumPerNet"
    relative: false
editPost:
    URL: "https://doi.org/10.48550/arXiv.2603.12857"
    Text: "arXiv"

---

---

##### Related

+ [Paper](https://doi.org/10.48550/arXiv.2603.12857)
+ [GitHub repository](https://github.com/giuliobarl/LumPerNet)

---

##### Abstract

Perovskite solar cells achieve remarkable power conversion efficiencies, yet operational stability remains a major barrier to large-scale deployment.
Reliable and rapid assessment of device state of health is therefore essential.
Conventional electrical diagnostics, such as illuminated current-voltage (J--V) sweeps, provide accurate performance metrics but are time-consuming and do not resolve spatially localized degradation, motivating non-invasive imaging-based alternatives.
A deep-learning framework is introduced to estimate PSC efficiency retention, $R_\mathrm{PCE}=\mathrm{PCE}_t/\mathrm{PCE}_0$, directly from multimodal luminescence imaging acquired during device aging.
Each sample combines electroluminescence (EL), open-circuit photoluminescence (PLoc), and short-circuit photoluminescence (PLsc) at an aged state with device-specific reference images at $t=0$, enabling learning of degradation-relevant spatial changes.
LumPerNet, a compact convolutional neural network, is benchmarked against a spatially homogenized control in which each luminescence channel is replaced by its spatial average while retaining the same learning framework and leakage-aware protocol.
The comparison indicates that global luminescence evolution contains most of the predictive signal, while spatial information provides a secondary contribution to robustness.
These results establish spatially resolved luminescence imaging as a practical route for accelerated stability testing and non-invasive degradation monitoring in perovskite photovoltaics.

---

##### Figure 1: The schematic shows the protocol for training the LumPerNet models.

![](convnet.png)

---

##### Citation

Barletta, Giulio, et al.
"Quantifying Perovskite Solar Cell Degradation via Machine Learning from Spatially Resolved Multimodal Luminescence Time Series."
arXiv preprint
arXiv:2603.12857
(2026).
https://doi.org/10.48550/arXiv.2603.12857.

```BibTeX
@article{barletta2026quantifying,
  title={Quantifying Perovskite Solar Cell Degradation via Machine Learning from Spatially Resolved Multimodal Luminescence Time Series},
  author={Barletta, Giulio and Ternes, Simon and Ali, Saif and Abbas, Zohair and Ostendi, Chiara and D'Addio, Marialucia and Magliano, Erica and Asinari, Pietro and Chiavazzo, Eliodoro and Di Carlo, Aldo},
  journal={arXiv preprint arXiv:2603.12857},
  year={2026},
  doi={https://doi.org/10.48550/arXiv.2603.12857}
}
```