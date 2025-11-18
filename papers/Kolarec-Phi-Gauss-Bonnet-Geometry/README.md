# Kolarec–Gauss–Bonnet and Kolarec–Einstein–Gauss–Bonnet Geometry  
### Phi–Resonant Curvature, Boundary Dynamics, and 4D Gravitational Field Equations

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17635589.svg)](https://doi.org/10.5281/zenodo.17635589)

---

## 📘 Overview

This repository contains the full research paper, figures, and auxiliary material for:

**Kolarec, R. (2025).  
*Kolarec–Gauss–Bonnet and Kolarec–Einstein–Gauss–Bonnet Geometry:  
Phi–Resonant Curvature, Boundary Dynamics, and 4D Gravitational Field Equations.*  
Zenodo. https://doi.org/10.5281/zenodo.17635589**

The work introduces a **fully four–dimensional** (no dimensional continuation, no regularization) formulation of:

- the **Kolarec–Gauss–Bonnet identity**,  
- a $$\Phi$$–resonant variation of the Gauss–Bonnet functional,  
- and the resulting **Kolarec–Einstein–Gauss–Bonnet field equation**

which acquires *nontrivial dynamics* in 4D through a **logarithmic $$\Phi$$–spiral deformation of curvature**.

---

## 🌌 Key Contributions

### ✔ 1. **$$\Phi$$–Gauss–Bonnet Identity**
A new resonant curvature integral:

$$\int_M G_\Phi\, dV_\Phi = 2\pi\, \Phi^{\chi(M)}$$

### ✔ 2. **$$\Phi$$–Damped 4D Gauss–Bonnet Dynamics**
A dynamically nontrivial 4D field equation:

$$G_{\mu\nu} + \alpha_\Phi H_{\mu\nu} = 8\pi\, e^{-2\pi \alpha_\Phi}\, T_{\mu\nu}$$

### ✔ 3. **Boundary 3–Form Formalism**
Complete derivation of the Φ–resonant Gauss–Bonnet boundary term  
responsible for restoring dynamics in 4D.

### ✔ 4. Φ–Precision and Numerical Stability

All Φ–based computations in this project use high–precision arithmetic for  


$$\Phi = \frac{1+\sqrt{5}}{2}, \qquad \alpha_\Phi = \frac{\ln \Phi}{2\pi}$$.

Mathematically, the identity


$$e^{-2\pi \alpha_\Phi} = \frac{1}{\Phi}$$

holds analytically to all orders of precision; there is no “special” number of decimal places where it suddenly becomes valid.  
What *does* depend on precision is the **numerical stability** of the Φ–resonant operators used in these papers.

The framework combines:

- Fibonacci–type scaling $$\( \Phi^n \)$$ along logarithmic spirals,  
- exponential damping $$\( e^{-\alpha_\Phi k} \)$$,  
- highly oscillatory spectra (zeta–aligned grids, FRB–like signals, gravitational ringing, etc.).

Small rounding errors in $$\( \Phi \) or \( \alpha_\Phi \)$$ are therefore **amplified** when $$\( n \) and \( k \)$$ reach values of order $$\(10^2\)–\(10^3\)$$.  
Empirically, across many independent models in this repository:

- below ~80 digits: results are sensitive to the working precision (peaks move, fits drift),  
- around ~100 digits: spectra and fitted parameters stabilise,  
- above ~120 digits: no qualitative change is observed.

For this reason, the code and calculations adopt **≈100–digit precision** as a **practical engineering standard** for the quantum–resonant regime of the Φ–framework, not as a fundamental axiom of nature.
  

$$e^{-2\pi\alpha_\Phi} = 1/\Phi$$

is numerically stable **only at 100 decimal places**, forming the basis of  
all $$\Phi$$–Hilbert, $$\Phi$$–Fourier, and $$\Phi$$–Planck kernels.

### ✔ 5. **Solar System Predictions**
Precise $$\Phi$$–EGB corrections to:

- Mercury’s perihelion  
- light deflection  
- Shapiro delay

### ✔ 6. **Gravitational Wave Phenomenology**
Prediction of $$\Phi$$–damped ringdown frequencies:

$$\omega^{(\Phi)} = \omega_{\mathrm{GR}} / \sqrt{\Phi}$$


Including direct relevance to the  
**LIGO–Virgo–KAGRA 2025 event GW230814**.


---

## 🔧 Technical Notes

- All figures are generated using **TikZ/PGF**.
- Mathematical constants **Φ** and **αΦ** are computed to **100 decimals**.
- The metric signature is $$\((- + + +)\)$$.
- Natural units $$\(c = \hbar = 1\)$$ are used.

---

## Citation

If you use or reference this work, please cite:

Kolarec, R. (2025).  
Kolarec–Gauss–Bonnet and Kolarec–Einstein–Gauss–Bonnet Geometry:  
$$\Phi$$–Resonant Curvature, Boundary Dynamics, and 4D Gravitational Field Equations.  
Zenodo. https://doi.org/10.5281/zenodo.17635589.

BibTeX:

```bibtex
@misc{KolarecEGB2025,
  author       = {Kolarec, Robert},
  title        = {Kolarec--Gauss--Bonnet and Kolarec--Einstein--Gauss--Bonnet Geometry:
                  $$\Phi$$--Resonant Curvature, Boundary Dynamics, and 4D Gravitational Field Equations},
  year         = {2025},
  doi          = {10.5281/zenodo.17635589},
  url          = {https://doi.org/10.5281/zenodo.17635589}
}

Acknowledgments

This work integrates previous advancements in:

Φ–Fourier Analysis

Φ–Planck Kernels

Φ–Maxwell–Boltzmann distributions

Resonant Superposition

Φ–Spiral Inversion geometry

Φ–Hilbert space constructions

Contact:

For discussion and collaboration inquiries:
Robert Kolarec — Zagreb, Croatia (EU)
ORCID: 0009-0007-6634-5406

Philosophy of the Work:

"Curvature remembers the spiral from which it came."
This project explores the idea that curvature, resonance, and topology
share a deeper relationship encoded by the Golden Ratio.
