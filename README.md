# Physics Simulations & Graphs

Notebooks that simulate and plot physical phenomena.

## Diffraction Rings: Crystallography of Iron

[`DiffractionRingsSimulation.ipynb`](DiffractionRingsSimulation.ipynb) simulates a **powder X-ray
diffraction** pattern for iron in its two cubic phases:

- **BCC** (body-centred cubic, α-Fe) and **FCC** (face-centred cubic, γ-Fe)
- Cu Kα radiation (λ = 1.54 Å), lattice parameter a = 3 Å

What the notebook does:
1. Generates the Miller indices (h, k, l) and computes the **structure factor** of each lattice, which
   shows the extinction rules that make BCC and FCC look different
2. Computes interplanar spacings and **Bragg angles** 2θ for the allowed reflections
3. Plots structure factors per plane and summary tables
4. Draws the **Debye–Scherrer rings**, with each ring labelled by its (h, k, l) plane

> Simplifications: only one atom type, and no atomic form factor. That's enough to identify which planes
> diffract, but not to get realistic intensities.

An interactive version runs on my site: https://alltairas.github.io/

## Requirements

```bash
pip install numpy pandas matplotlib jupyter
```
