---
title: "Side-Channel Security in Multi-Tenant Quantum Computers"
date: 2025-02-01
summary: "Crosstalk-based side-channel attacks on multi-tenant NISQ hardware — deciphering a victim's circuit with graph neural networks."
tags: ["security", "side channels", "NISQ"]
showDate: false
---

When multiple users share a quantum computer, **crosstalk leaks information across tenant boundaries**. This project designed an attack that deduces confidential user data by exploiting a crosstalk-based side channel on quantum hardware, using a **graph neural network** to decipher the victim's circuit from the information leak — and examined side-channel vulnerabilities in superconducting qubit readout architectures.

## Key results

- Demonstrated circuit-recovery attacks over crosstalk side channels on multi-tenant NISQ computers (NDSS 2025).
- Characterized side-channel vulnerabilities specific to superconducting readout architectures (QCE 2024).

<!-- figure slot: add ![overview](figure.png) here -->

## Papers

**Crosstalk-induced Side Channel Threats in Multi-Tenant NISQ Computers**
Navnil Choudhury, Chaithanya Naik Mude, Sanjay Das, Preetham Tikkireddi, Swamit Tannu, Kanad Basu. *NDSS 2025.*
[[Paper]](https://www.ndss-symposium.org/wp-content/uploads/2025-2185-paper.pdf)

**Understanding Side-Channel Vulnerabilities in Superconducting Qubit Readout Architectures**
Satvik Maurya, Chaithanya Naik Mude, Benjamin Lienhard, Swamit Tannu. *QCE 2024.*
[[Paper]](https://ieeexplore.ieee.org/document/10821389)

## Code

Code available upon request — public release coming soon.

## BibTeX

```bibtex
@inproceedings{choudhury2025crosstalk,
  title     = {Crosstalk-induced Side Channel Threats in Multi-Tenant NISQ Computers},
  author    = {Choudhury, Navnil and Mude, Chaithanya Naik and Das, Sanjay and Tikkireddi, Preetham and Tannu, Swamit and Basu, Kanad},
  booktitle = {Network and Distributed System Security Symposium (NDSS)},
  year      = {2025}
}

@inproceedings{maurya2024sidechannel,
  title     = {Understanding Side-Channel Vulnerabilities in Superconducting Qubit Readout Architectures},
  author    = {Maurya, Satvik and Mude, Chaithanya Naik and Lienhard, Benjamin and Tannu, Swamit},
  booktitle = {IEEE International Conference on Quantum Computing and Engineering (QCE)},
  year      = {2024}
}
```
