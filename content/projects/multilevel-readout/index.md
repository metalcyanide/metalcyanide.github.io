---
title: "Scaling Multi-Level Superconducting Qubit Readout with ML"
date: 2025-06-01
summary: "Hardware-efficient ML architectures for superconducting qubit readout — 16% accuracy gain, matched filters under 8% FPGA resources, 6.6% multi-level improvement."
tags: ["superconducting", "readout", "ML", "FPGA"]
showDate: false
---

Fast, accurate qubit readout is a bottleneck for scaling superconducting quantum computers. This line of work designs **hardware-efficient machine-learning readout architectures** that fit on FPGA-class control hardware and extend to multi-level (qutrit+) readout.

## Key results

- **16% relative improvement in readout accuracy** by identifying relaxations that occur during readout (ISCA 2023).
- Matched-filter architecture using **less than 8% of FPGA resources**.
- **6.6% relative accuracy improvement for multi-level readout** with better leakage detection during readout (DAC 2025).

<!-- figure slot: add ![overview](figure.png) here -->

## Papers

**Efficient and Scalable Architectures for Multi-level Superconducting Qubit Readout**
Chaithanya Naik Mude, Satvik Maurya, Benjamin Lienhard, Swamit Tannu. *DAC 2025.*
[[Paper]](https://ieeexplore.ieee.org/abstract/document/11133314)

**Scaling Qubit Readout with Hardware Efficient Machine Learning Architectures**
Satvik Maurya, Chaithanya Naik Mude, William D. Oliver, Benjamin Lienhard, Swamit Tannu. *ISCA 2023.*
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3579371.3589042)

## Code

Code available upon request — public release coming soon.

## BibTeX

```bibtex
@inproceedings{mude2025multilevel,
  title     = {Efficient and Scalable Architectures for Multi-level Superconducting Qubit Readout},
  author    = {Mude, Chaithanya Naik and Maurya, Satvik and Lienhard, Benjamin and Tannu, Swamit},
  booktitle = {62nd Design Automation Conference (DAC)},
  year      = {2025}
}

@inproceedings{maurya2023scaling,
  title     = {Scaling Qubit Readout with Hardware Efficient Machine Learning Architectures},
  author    = {Maurya, Satvik and Mude, Chaithanya Naik and Oliver, William D. and Lienhard, Benjamin and Tannu, Swamit},
  booktitle = {50th International Symposium on Computer Architecture (ISCA)},
  year      = {2023},
  doi       = {10.1145/3579371.3589042}
}
```
