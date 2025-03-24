---
title: "Energy-GNoME: A Living Database of Selected Materials for Energy Applications" 
date: 2024-11-15
lastmod: 2024-11-15
tags: ["Advanced Materials", "Energy Materials", "Materials Science", "Artificial Intelligence", "Machine Learning", "Deep Learning", "Computational Chemistry", "Dataset", "Thermoelectric", "Battery", "Perovskite"]
author: ["Paolo De Angelis","Giovanni Trezza", "Giulio Barletta", "Pietro Asinari", "Eliodoro Chiavazzo"]
description: "This paper presents the novel Energy-GNoME database and the related protocol. Preprint published on arXiv, 2024." 
summary: "This paper presents the novel Energy-GNoME database and the related protocol." 
cover:
    image: "egnome.png"
    alt: "Energy-GNoME"
    relative: false
editPost:
    URL: "https://arxiv.org/abs/2411.10125"
    Text: "arXiv"

---

---

##### Download

+ [Paper](energy-gnome.pdf)
+ [Online interactive database](https://paolodeangelis.github.io/Energy-GNoME/)

---

##### Abstract

Artificial Intelligence (AI) in materials science is driving significant advancements in the discovery of advanced materials for energy applications. The recent GNoME protocol identifies over 380,000 novel stable crystals. From this, we identify over 33,000 materials with potential as energy materials forming the Energy-GNoME database. Leveraging Machine Learning (ML) and Deep Learning (DL) tools, our protocol mitigates cross-domain data bias using feature spaces to identify potential candidates for thermoelectric materials, novel battery cathodes, and novel perovskites. Classifiers with both structural and compositional features identify domains of applicability, where we expect enhanced accuracy of the regressors. Such regressors are trained to predict key materials properties like, thermoelectric figure of merit (zT), band gap (Eg), and cathode voltage (ΔVc). This method significantly narrows the pool of potential candidates, serving as an efficient guide for experimental and computational chemistry investigations and accelerating the discovery of materials suited for electricity generation, energy storage and conversion.

---

##### Figure 1: The schematic shows the protocol for creating the Energy-GNoME database.

![](egnome.png)

---

##### Citation

De Angelis, P.; Trezza, G.; Barletta, G.; Asinari, P.; Chiavazzo, E. "Energy-GNoME: A Living Database of Selected Materials for Energy Applications". arXiv November 15, 2024. doi: 10.48550/arXiv.2411.10125.

```BibTeX
@misc{deangelis_energy-gnome:_2024,
    title = {Energy-{GNoME}: {A} {Living} {Database} of {Selected} {Materials} for {Energy} {Applications}},
    shorttitle = {Energy-{GNoME}},
    url = {http://arxiv.org/abs/2411.10125},
    doi = {10.48550/arXiv.2411.10125},
    urldate = {2024-12-03},
    publisher = {arXiv},
    author = {De Angelis, Paolo and Trezza, Giovanni and Barletta, Giulio and Asinari, Pietro and Chiavazzo, Eliodoro},
    month = nov,
    year = {2024},
    note = {arXiv:2411.10125},
    keywords = {Condensed Matter - Materials Science, Condensed Matter - Other Condensed Matter, Computer Science - Machine Learning},
}
```