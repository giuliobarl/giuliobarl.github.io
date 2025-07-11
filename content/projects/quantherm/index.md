---
title: "QuanThermal" 
date: 2025-07-08
lastmod: 2025-07-08
tags: ["Quantum Computing", "Thermal Science", "Heat Conduction", "Variational Quantum
Algorithm", "Quantum Circuit Ansatz", "Real Data Loading / Encoding"]
author: ["Pietro Asinari, Giulio Barletta"]
description: "This repository contains the notebooks related to the publication Notes on Quantum Computing for Thermal Science" 
summary: "This repository contains the notebooks related to the publication Notes on Quantum Computing for Thermal Science"  
cover:
    image: "entanglement.jpg"
    alt: "QUANTHERMAL"
    relative: false
editPost:
    URL: "https://github.com/giuliobarl/QuanThermal"
    Text: "GitHub"

---

---

##### Related

+ [Paper](https://arxiv.org/pdf/2503.19109)

---

##### Description

# Quantum Computing for Thermal Science

This repository contains codes related to the publication "**Notes on Quantum Computing for Thermal Science**"([arXiv](https://arxiv.org/abs/2503.19109), [GitHub](https://github.com/giuliobarl/QuanThermal/blob/main/notes.pdf)). This document explores the potential of quantum computing for solving linear systems of interest in engineering. In particular, we focus on heat conduction as a paradigmatic example in thermal science.

March 2025 - [Pietro Asinari](https://staff.polito.it/pietro.asinari/), [Nada Alghamdi](https://www.polito.it/en/staff?p=106642), [Paolo De Angelis](https://paolodeangelis.github.io/), [Giulio Barletta](https://giuliobarl.github.io/), [Giovanni Trezza](https://www.grenoble-inp.fr/fr/personnel/giovanni-trezza), [Marina Provenzano](https://www.polito.it/en/staff?p=043095), [Matteo Maria Piredda](https://www.polito.it/en/staff?p=067867), [Matteo Fasano](https://www.polito.it/en/staff?p=026208), [Eliodoro Chiavazzo](https://www.polito.it/en/staff?p=eliodoro.chiavazzo).

Original scripts written by Pietro Asinari, adapted as notebooks by Giulio Barletta.

## Qiskit folder overview

This folder contains Jupyter notebooks demonstrating quantum computing algorithms using Qiskit. The aim is to explore quantum computing algorithms — especially VQE — for solving problems in heat conduction and thermal science, as well as illustrate physical analogies and competitive dynamics using quantum circuits.

### [`VQE-example_v15.ipynb`](https://github.com/giuliobarl/QuanThermal/blob/main/Qiskit/VQE-example_v15.ipynb)

Implements the Variational Quantum Eigensolver (VQE) to approximate the solution of a linear system derived from the finite-difference discretization of the 1D heat conduction equation.

Key features:

- Constructs a quantum observable mimicking the system matrix for heat transfer.
- Uses VQE to find the ground state (analogous to updated temperature profiles).
- Demonstrates encoding/normalization and de-normalization steps tied to physical temperature fields.
- Relates directly to Sections 3–3.6 of the paper.

Libraries Used:

- `qiskit`
- `matplotlib`, `numpy`, `scipy`, `statistics`, `time`

### [`two-athletes_v01.ipynb`](https://github.com/giuliobarl/QuanThermal/blob/main/Qiskit/two-athletes_v01.ipynb)

Illustrates quantum modeling of strategic competition between two agents (athletes) as described in Appendix A of the paper.

Key features:

- Each athlete's strategy is encoded as a quantum state.
- Simulates the outcomes using unitary operations and measurement statistics.
- Shows how quantum superposition and entanglement can capture correlated strategic behavior (e.g., collaboration, competition).
- Acts as a pedagogical analogy for quantum entanglement in decision-making.
- Corresponds to Appendix A of the paper ("*Two-athlete strategy*").

Libraries Used:

- `qiskit`
- `numpy`

### [`real-data-loader_v06.ipynb`](https://github.com/giuliobarl/QuanThermal/blob/main/Qiskit/real-data-loader-v06.ipynb)

Implements a recursive divide-and-conquer algorithm to prepare a quantum state that encodes a real-valued probability distribution:

- Based on the method by [Araujo et al.](https://www.nature.com/articles/s41598-021-85474-1)
- Computes a set of RY rotation angles to load real classical data into a quantum amplitude-encoded state.
- Executes the circuit and compares simulated measurement results with the original distribution.
- Corresponds to Appendix D of the paper ("*Real data loading/encoding*").

Libraries Used:

- `qiskit`
- `numpy`

---

##### Citation

Asinari, Pietro, et al. "Notes on Quantum Computing for Thermal Science." arXiv preprint arXiv:2503.19109 (2025).

```BibTeX
@article{asinari2025notes,
  title={Notes on Quantum Computing for Thermal Science},
  author={Asinari, Pietro and Alghamdi, Nada and De Angelis, Paolo and Barletta, Giulio and Trezza, Giovanni and Provenzano, Marina and Piredda, Matteo Maria and Fasano, Matteo and Chiavazzo, Eliodoro},
  journal={arXiv preprint arXiv:2503.19109},
  year={2025}
}
```