---
title: "Enhanced Neutral Atom Readout with ML"
date: 2025-04-01
summary: "Modular, scalable ML models for neutral-atom qubit readout — 70× smaller models than state of the art, plus image denoising for fast, accurate readout."
tags: ["neutral atoms", "readout", "ML"]
showDate: false
---

Neutral-atom platforms read out qubits by imaging atom fluorescence — a noisy, camera-limited process. This project builds **modular and scalable machine-learning models** for neutral-atom qubit readout that leverage each site's error profile, and an **image-denoising** front end that enables fast and accurate readout. Presented at the [APS March Meeting 2025](https://meetings-archive.aps.org/smt/2025/mar-b09/12/).

## Key results

- **70× reduction in model size** compared to the state-of-the-art solution, at matched accuracy.
- Matched-filter measurement of neutral-atom qubits (with the Saffman and Gauthier groups), published in *Physical Review Applied*.

<!-- figure slot: add ![overview](figure.png) here -->

## Papers

**Enabling Fast and Accurate Neutral Atom Readout through Image Denoising**
Chaithanya Naik Mude, Linipun Phuttitarn, Satvik Maurya, Kunal Sinha, Mark Saffman, Swamit Tannu. *Preprint.*
[[arXiv]](https://arxiv.org/abs/2504.08170)

**Efficient Measurement of Neutral-Atom Qubits with Matched Filters**
Robert M. Kent, Linipun Phuttitarn, Chaithanya N. Mude, Swamit Tannu, Mark Saffman, Gregory Lafyatis, Daniel J. Gauthier. *Physical Review Applied.*
[[arXiv]](https://arxiv.org/abs/2510.25982)

## Code

Code available upon request — public release coming soon.

## BibTeX

```bibtex
@article{mude2025denoising,
  title   = {Enabling Fast and Accurate Neutral Atom Readout through Image Denoising},
  author  = {Mude, Chaithanya Naik and Phuttitarn, Linipun and Maurya, Satvik and Sinha, Kunal and Saffman, Mark and Tannu, Swamit},
  journal = {arXiv preprint arXiv:2504.08170},
  year    = {2025}
}

@article{kent2025matched,
  title   = {Efficient Measurement of Neutral-Atom Qubits with Matched Filters},
  author  = {Kent, Robert M. and Phuttitarn, Linipun and Mude, Chaithanya N. and Tannu, Swamit and Saffman, Mark and Lafyatis, Gregory and Gauthier, Daniel J.},
  journal = {Physical Review Applied},
  year    = {2025}
}
```
