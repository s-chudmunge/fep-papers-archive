# Physics-Guided Representation Learning from Free Energy Perturbation Data

> **Curated chronological research archive (1954–2026) spanning Statistical Mechanics, Alchemical Free Energy Perturbation (FEP), 3D Equivariant Deep Learning, Multi-Fidelity Surrogates, and Candidate Down-Selection.**

🌐 **Live Archive Website:** [https://s-chudmunge.github.io/fep-papers-archive/](https://s-chudmunge.github.io/fep-papers-archive/)

---

## Overview

Discovering therapeutic molecules is fundamentally a search for ligands that bind tightly and selectively to biological targets. For decades, predicting binding affinity has been divided between fast empirical shortcuts and computationally intensive alchemical simulations like **Free Energy Perturbation (FEP)**. 

While FEP achieves sub-1 kcal/mol chemical accuracy, its high computational cost limits broad exploration across combinatorial chemical spaces. Conversely, modern 3D equivariant neural networks evaluate molecules in milliseconds but struggle to generalize across unfamiliar chemical series without physical constraints.

This archive curates landmark literature establishing the modern synthesis of these fields:
1. **FEP & Thermodynamic Foundations:** Zwanzig perturbation theory, Bennett Acceptance Ratio (BAR), Multistate BAR (MBAR), and prospective industrial RBFE benchmarks.
2. **Equivariant & Geometric Deep Learning:** E(n) and E(3)-equivariant graph neural networks (EGNN, NequIP, MACE) mapping 3D molecular conformations to potential energy surfaces.
3. **Physics-Informed ML & Δ-Learning:** Learning residual corrections between approximate models and physical simulations under thermodynamic constraints.
4. **Perturbation Graphs & Cycle Closure:** Exploiting closed thermodynamic cycles ($\sum_{\text{cycle}} \Delta\Delta G = 0$) to eliminate non-physical path dependency and filter simulation errors.
5. **Multi-Fidelity Statistical Learning:** Kennedy–O'Hagan Gaussian process frameworks and deep kernel learning fusing scarce physical experiments with high-throughput simulation data.
6. **Active Learning & Candidate Down-Selection:** Multi-information source Bayesian optimization policies prioritizing simulation budgets and compound synthesis.

---

## Features of the Web Archive

- **Interactive Search:** Instant filtering across paper titles, author names, journals, and key findings.
- **Pillar Filtering:** One-click toggling across the 6 core research disciplines.
- **Main Result Highlights:** Every paper includes a plain-language explanation and primary quantitative metric / outcome.
- **Dark / Light Theme:** Responsive styling with automatic system preference detection and manual toggle.
- **Direct DOI & arXiv Access:** Immediate links to primary literature sources.

---

## Local Development

To run the archive locally:

```bash
git clone https://github.com/s-chudmunge/fep-papers-archive.git
cd fep-papers-archive
python3 -m http.server 8080
```

Open [http://localhost:8080/](http://localhost:8080/) in your browser.

---

## Citation & Metadata

Curated and maintained by [Sankalp Chudmunge](https://github.com/s-chudmunge).
