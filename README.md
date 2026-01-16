# SFH Galaxy Rotation Curves — Reproducible Analysis

This repository provides the full reproducible analysis associated with the paper:

**“Galaxy Rotation Curves Without Dark Matter Halos:  
A First-Principles Causal Framework (SFH Field Theory)”**  
Daniel Beaupré (2026)

The Spacetime Flow Hypothesis (SFH) models gravity as resistance to the flow of proper time,
described by a Lorentz-invariant vector field and a scalar resistance function.
This repository contains the notebooks, scripts, and input data required to reproduce
the galaxy rotation curve results presented in the paper.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/dbeaup01/<REPO_NAME>/blob/main/<NOTEBOOK_NAME>.ipynb
)

---

## Repository Contents

The associated manuscript is archived on Zenodo and should be cited independently:

Beaupré, D. (2026).  
*Galaxy Rotation Curves Without Dark Matter Halos: A First-Principles Causal Framework (SFH Field Theory).*  
Zenodo. (https://doi.org/10.5281/zenodo.18136466)

### 📓 Interactive Notebook
- `Galaxy_Rotation_Notebook.ipynb`  
  Primary analysis notebook reproducing individual galaxy rotation curves,
  including:
  - baryonic mass profiles
  - Poisson → Laplace transition
  - azimuthal (spin) flow component
  - combined SFH velocity predictions

### 📦 Batch Processing Tools
- `SFH_MultiGalaxy_BatchKit.zip`  
  Scripts and configuration files for running the SFH rotation model across
  multiple galaxies in a standardized, repeatable manner.

### 📦 Input Data
- `Rotmod_LTG.zip`  
  SPARC-compatible baryonic rotation model files (`rotmod`) used as inputs
  for the SFH analysis. These files contain observationally derived stellar and
  gas mass distributions only.

---

## Scope and Modeling Notes

- This analysis **does not assume dark matter halos**.
- Galaxy rotation curves are modeled using **baryonic mass distributions only**,
  combined with SFH-motivated flow dynamics.
- Certain shape and transition parameters are treated **per galaxy** and are
  explicitly acknowledged as phenomenological at this stage.
- No empirical force laws or MOND-style interpolation functions are used.

This repository is intended as a **transparent, reproducible validation test**
of the SFH framework in the context of galaxy dynamics.

---

## Reproducibility

All figures and tables in the paper can be regenerated using the provided notebook
and input data. No proprietary software is required.

Python ≥ 3.9  
Key dependencies:
- numpy
- scipy
- pandas
- matplotlib
- astropy

---

## Citation

If you use or reference this work, please cite:

Beaupré, D. (2026).  
*Galaxy Rotation Curves Without Dark Matter Halos: A First-Principles Causal Framework.*  
Zenodo. DOI: (add DOI here)

---

## Contact

Correspondence and reproducibility questions may be submitted via GitHub Issues
on this repository.
