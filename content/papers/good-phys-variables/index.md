---
title: "Learning Effective Good Variables from Physical Data" 
date: 2024-07-12
lastmod: 2024-07-18
tags: ["Machine Learning", "Primitive Variable Analysis", "Physical Property Invariance", "Feature Grouping"]
author: ["Giulio Barletta", "Giovanni Trezza", "Eliodoro Chiavazzo"]
description: "This paper presents two novel approaches to the discovery of possible groups or combinations of primitive variables. Published in Machine Learning and Knowledge Extraction, 2024." 
summary: "This paper presents two novel approaches to the discovery of possible groups or combinations of primitive variables." 
cover:
    image: "good_vars.webp"
    alt: "Feature grouping protocol"
    relative: false
editPost:
    URL: "https://www.mdpi.com/2504-4990/6/3/77"
    Text: "Machine Learning and Knowledge Extraction"

---

---

##### Download

+ [Paper](effective-good.pdf)
+ [Code](https://github.com/giuliobarl/GoodPhysVariables)
+ [Data](https://zenodo.org/records/11639037)

---

##### Abstract

We assume that a sufficiently large database is available, where a physical property of interest and a number of associated ruling primitive variables or observables are stored. We introduce and test two machine learning approaches to discover possible groups or combinations of primitive variables, regardless of data origin, being it numerical or experimental: the first approach is based on regression models, whereas the second on classification models. The variable group (here referred to as the new effective good variable) can be considered as successfully found when the physical property of interest is characterized by the following effective invariant behavior: in the first method, invariance of the group implies invariance of the property up to a given accuracy; in the other method, upon partition of the physical property values into two or more classes, invariance of the group implies invariance of the class. For the sake of illustration, the two methods are successfully applied to two popular empirical correlations describing the convective heat transfer phenomenon and to the Newton’s law of universal gravitation.

---

##### Figure 1: Overview of the protocol used to detect possible symmetries of a target property of interest with respect to its input variables.

![](good_vars.webp)

---

##### Citation

Barletta, G.; Trezza, G.; Chiavazzo, E. Learning Effective Good Variables from Physical Data. Mach. Learn. Knowl. Extr. 2024, 6, 1597-1618. https://doi.org/10.3390/make6030077

```BibTeX
@Article{make6030077,
AUTHOR = {Barletta, Giulio and Trezza, Giovanni and Chiavazzo, Eliodoro},
TITLE = {Learning Effective Good Variables from Physical Data},
JOURNAL = {Machine Learning and Knowledge Extraction},
VOLUME = {6},
YEAR = {2024},
NUMBER = {3},
PAGES = {1597--1618},
URL = {https://www.mdpi.com/2504-4990/6/3/77},
ISSN = {2504-4990},
DOI = {10.3390/make6030077}
}
```
