---
layout: page
title: Plasma-Based Nitrogen Fixation
description: NOx formation and arc stability in a pin-to-pin arc plasma reactor
img: assets/img/nitrogen.png
importance: 1
category: work
related_publications: true
---

## Project Overview

This project systematically investigated atmospheric-pressure nitrogen fixation using a pin-to-pin arc plasma reactor. The effects of key operating parameters on NO formation, NO selectivity, energy cost, and arc stability were evaluated as a promising alternative to the conventional Haber–Bosch process.

A minimum energy cost of approximately **2.5 MJ/mol** was achieved, demonstrating the potential of pin-to-pin arc plasma technology as an energy-efficient and scalable nitrogen fixation process.

---

## My Contribution

- **Experimental investigation**: Evaluated the effects of pin-to-pin gap, swirl intensity, gas flow rate, oxygen concentration, and delivered power on NOx formation and arc stability
- **Arc dynamics analysis**: Analyzed arc oscillation behavior using high-speed imaging combined with spectral proper orthogonal decomposition (SPOD)
- **Plasma diagnostics**: Characterized thermal state and reactive species distribution using optical emission spectroscopy (OES) and sCMOS imaging
- **NOx quantification**: Measured outlet gas composition using Fourier-transform infrared (FTIR) spectroscopy

---

## Key Results

### Effect of Arc Gap & Swirl

- NO concentration increased with increasing pin-to-pin gap under all conditions
- Smaller swirl hole (1 mm, S_g = 4.37) produced higher NO than larger hole (3 mm, S_g = 1.45)
- Energy cost decreased from ~4.5 MJ/mol → **~2.5 MJ/mol** as gap increased to 300 mm

### Effect of Oxygen Concentration

- **Highest NO production** at ~30% O₂ (optimal balance between oxygen radicals and electron density)
- **Lowest energy cost** at ~50% O₂ (highest total NOx production)
- Arc stability deteriorated at higher O₂ fractions due to electron attachment

### Effect of Delivered Power

- Higher power enabled stable operation at longer arc lengths
- Lower power reduced energy cost but limited maximum sustainable arc length
- Optimal trade-off exists between energy efficiency and discharge stability

---

## Arc Dynamics (SPOD Analysis)

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/nitrogen_spod.png" title="SPOD analysis of arc dynamics" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
SPOD analysis of arc column dynamics. Smaller swirl holes shifted dominant oscillation frequencies toward higher values (96.7 Hz vs 28.2 Hz), indicating more complex plasma dynamics.
</div>

---

## Skills & Tools

- **Diagnostics**: High-speed imaging, SPOD, OES, sCMOS, FTIR
- **Analysis**: Arc stability characterization, energy cost evaluation, NO selectivity analysis
- **Programming**: Python (SPOD analysis, data visualization)

---

## Takeaways

- Arc elongation is the most effective strategy for simultaneously enhancing NO production and reducing energy cost
- Oxygen concentration critically governs both nitrogen oxidation efficiency and arc stability — an intermediate O₂ fraction (~30%) provides the optimal balance
- SPOD analysis revealed that stronger swirl intensity shifts arc oscillation toward higher frequencies, enhancing plasma–gas interaction

---

## Related Publication

- H. S. Choi, S. Choi, **S. Choi**, S. U. Hassan, G. Kim, D. H. Lee, M. S. Bak, J. Choi, _"Nitrogen Fixation Using a Pin-to-Pin Arc Plasma: Effects of Operating Parameters on NOx Formation Characteristics and Arc Stability,"_ **Chem. Eng. J.** (under review).
