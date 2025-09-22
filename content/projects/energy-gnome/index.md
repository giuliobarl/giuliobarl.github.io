---
title: "Energy-GNoME"
date: 2025-09-16
lastmod: 2025-09-16
tags: ["Energy Materials", "Artificial Intelligence", "Machine Learning", "Deep Learning", "Thermoelectric", "Battery", "Perovskite"]
author: ["Paolo De Angelis", "Giulio Barletta"]
description: "This repository contains the database, documentation, Python library (coming soon), and notebooks used to build the Energy-GNoME database." 
summary: "This repository contains the database, documentation, Python library (coming soon), and notebooks used to build the Energy-GNoME database." 
cover:
    image: "egnome.png"
    alt: "Energy-GNoME"
    relative: false
editPost:
    URL: "https://github.com/paolodeangelis/Energy-GNoME"
    Text: "GitHub"

---

---

##### Related

+ [Paper](https://doi.org/10.1016/j.egyai.2025.100605)
+ [Online interactive database](https://paolodeangelis.github.io/Energy-GNoME/)

---

##### Description

This repository contains the database, documentation, Python library (coming soon), and notebooks used to build the Energy-GNoME database.

The purpose of this repository is to enable reproducibility and, more importantly, to support the continuous integration of your data points for model training, as the database is designed as a living database.

For further details, refer to the associated article.

---

##### Overview of the protocol for creating the Energy-GNoME database.

![](egnome.png)

---

##### Citation

Paolo De Angelis, Giulio Barletta, Giovanni Trezza, Pietro Asinari, Eliodoro Chiavazzo,
Energy-GNoME: A living database of selected materials for energy applications,
Energy and AI,
Volume 22,
2025,
100605,
ISSN 2666-5468,
https://doi.org/10.1016/j.egyai.2025.100605.

```BibTeX
@article{DEANGELIS2025100605,
    title = {Energy-GNoME: A living database of selected materials for energy applications},
    journal = {Energy and AI},
    volume = {22},
    pages = {100605},
    year = {2025},
    issn = {2666-5468},
    doi = {https://doi.org/10.1016/j.egyai.2025.100605},
    url = {https://www.sciencedirect.com/science/article/pii/S2666546825001375},
    author = {Paolo {De Angelis} and Giulio Barletta and Giovanni Trezza and Pietro Asinari and Eliodoro Chiavazzo},
    keywords = {Energy materials, Artificial Intelligence, Machine Learning, Deep Learning, Thermoelectric, Battery, Perovskite},
    abstract = {Artificial Intelligence (AI) in materials science is driving significant advancements in the discovery of advanced materials for energy applications. The recent GNoME protocol identifies over 380,000 novel stable crystals. From this, we identify over 38,500 materials with potential as energy materials forming the core of the Energy-GNoME database. Our unique combination of Machine Learning (ML) and Deep Learning (DL) tools mitigates cross-domain data bias using feature spaces, thus identifying potential candidates for thermoelectric materials, novel battery cathodes, and novel perovskites. First, classifiers with both structural and compositional features detect domains of applicability, where we expect enhanced reliability of regressors. Here, regressors are trained to predict key materials properties, like thermoelectric figure of merit (zT), band gap (Eg), and cathode voltage (ΔVc). This method significantly narrows the pool of potential candidates, serving as an efficient guide for experimental and computational chemistry investigations and accelerating the discovery of materials suited for electricity generation, energy storage and conversion.}
}
```