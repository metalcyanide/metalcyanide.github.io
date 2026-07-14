---
title: "Adaptive Leakage Detection for Quantum Error Correction"
date: 2025-10-01
summary: "Speculation strategies that detect and mitigate leakage errors in QEC codes — 16% better logical error rate, 2–3× less leakage accumulation."
tags: ["QEC", "leakage", "decoding"]
showDate: false
---

Leaked qubits silently corrupt syndrome extraction and poison decoding in quantum error-correcting codes. This project designs **leakage speculation** strategies that precisely detect and mitigate leakage errors across QEC codes, plus an adaptive strategy that reduces how long leakage lingers in the code.

## Key results

- **16% improvement in logical error rate** from speculation-aware decoding.
- **2–3× reduction in leakage accumulation** via adaptive strategies across various QECCs, reducing QEC cycle time.
- Ongoing follow-up: an efficient ML decoder for the surface code that incorporates leakage speculation and uses adaptive RL to track evolving error profiles.

<!-- figure slot: add ![overview](figure.png) here -->

## Paper

**Accurate Leakage Speculation for Quantum Error Correction**
Chaithanya Naik Mude, Swamit Tannu. *MICRO 2025.*
[[Paper]](https://dl.acm.org/doi/full/10.1145/3725843.3756053)

## Code

Code available upon request — public release coming soon.

## BibTeX

```bibtex
@inproceedings{mude2025leakage,
  title     = {Accurate Leakage Speculation for Quantum Error Correction},
  author    = {Mude, Chaithanya Naik and Tannu, Swamit},
  booktitle = {58th IEEE/ACM International Symposium on Microarchitecture (MICRO)},
  year      = {2025},
  doi       = {10.1145/3725843.3756053}
}
```
