---
layout: page
title: Plasma Upcycling of Waste Plastic-Derived Oils
description: Surrogate-based chemical kinetic analysis of PPO pyrolysis in a hydrogen plasma reactor
img: assets/img/fuel.png
importance: 2
category: work
related_publications: true
---

## Project Overview

This project developed a surrogate-based kinetic modeling framework to systematically investigate the pyrolysis of waste plastic-derived oils (PPO) under high-temperature hydrogen plasma environments. Representative surrogates for PE-, PP-, and PS-derived oils were designed, and their pyrolysis characteristics were analyzed using 0-D and 1-D reactor models.

Hydrogen plasma can suppress carbon deposition, enhance heat transfer, and promote selective cracking toward light olefins — making it a promising route for circular plastic upcycling.

---

## My Contribution

- **Surrogate development**: Designed representative surrogate mixtures for PE-, PP-, and PS-derived oils based on extensive literature review
- **0-D simulation**: Analyzed temperature- and residence-time-dependent product distributions using a homogeneous batch reactor model
- **1-D simulation**: Investigated axial species evolution and product selectivity using a plug-flow reactor (PFR) model
- **Sensitivity analysis**: Identified dominant reaction pathways governing olefin and aromatic formation
- **Mechanism selection**: Adopted the CRECK_2023_TOT_HT mechanism (368 species, 14,462 reactions) for high-temperature hydrocarbon kinetics

---

## Key Results

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/fuel_regime.png" title="Temperature-residence-time regime map" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
Conceptual temperature–residence-time regime maps derived from 1-D simulations under hydrogen-plasma-relevant conditions.
</div>

### PE-derived oil
- At **2773 K**: 97.62% conversion with **C₂H₄ selectivity of 50.88%**
- Regime transition: β-scission → H-attack-driven C3→C2 transfer → secondary cracking

### PP-derived oil
- At **2773 K**: 98.32% conversion with deep-cracking products
  - CH₄: 30.13%, C₂H₄: 23.91%, C₂H₂: 21.18%, C₆H₆: 15.43%
- Branched backbone biases low-temperature chemistry toward iso-olefins and CH₄

### PS-derived oil
- At **2273 K**: C₆H₆ dominated (63.19%) despite 83.55% conversion
- At **2773 K**: PAH precursor (BIN1B) became major product (35.41%)
- Requires strict residence-time control to suppress PAH growth

---

## Temperature–Residence-Time Regime Map

| Feedstock | Temperature | Major Products | Key Pathways |
|-----------|-------------|---------------|--------------|
| PE/PP | Low (~1773 K) | C₃H₆, C₄H₆, C₂H₄ | β-scission |
| PE/PP | Intermediate (~2273 K) | C₂H₄ (dominant) | H-attack, C3→C2 transfer |
| PE/PP | High (~2773 K) | CH₄, C₂H₂, C₆H₆ | Secondary cracking |
| PS | Low–Intermediate | C₆H₆ (dominant) | Benzylic C–C scission |
| PS | High (~2773 K) | BIN1B, PAHs | HACA, PAC mechanisms |

---

## Skills & Tools

- **Simulation**: Ansys Chemkin-Pro, 0-D batch reactor, 1-D plug-flow reactor
- **Mechanism**: CRECK_2023_TOT_HT high-temperature kinetic mechanism
- **Analysis**: Reaction rate sensitivity analysis, surrogate design, regime mapping
- **Programming**: Python (data analysis and visualization)

---

## Takeaways

- Polymer-inherited hydrocarbon structure fundamentally governs pyrolysis behavior under plasma conditions
- For PE/PP feeds, intermediate severity (H-attack-dominated C3→C2 transfer) maximizes C₂H₄ selectivity
- PS feeds require careful residence-time management to suppress PAH growth
- Surrogate-based kinetic frameworks offer a practical and reproducible approach to mechanistic analysis of complex feedstocks

---

## Related Publication

- 📄 **S. Choi**, C. Jung, D. H. Lee, J. Choi, *"Chemical Kinetic Analysis of the Pyrolysis Process of Waste Plastic-Derived Oils in a Hydrogen Plasma Reactor,"* **Fuel** 421, 139022 (2026). [doi:10.1016/j.fuel.2026.139022](https://doi.org/10.1016/j.fuel.2026.139022)