# Bragg's Law Microwave Diffraction

## Overview
This experiment was performed at the University of Hawaiʻi at Mānoa in PHYS 274L. The diffraction of microwaves through a crystal lattice, made of styrofoam and steel balls, was measured to verify the first-order Bragg's Law. Data was collected across the 100, 110, and 210 plane and analyzed to determine the lattice constant of the crystal. Diffraction peaks were identified and compared to theoretical values.

## Methods
- Gaussian curve fitting to identify and characterize diffraction peaks
- Error propagation to calculate uncertainty in results
- Weighted average across all planes to determine final lattice constant

## Results
| Plane | Order | Lattice Constant [cm] |
|-------|-------|-----------------------|
| 100   | n=1   | 3.6 ± 0.5             |
| 100   | n=2   | 3.82 ± 0.18           |
| 110   | n=1   | 3.79 ± 0.07           |
| 210   | n=1   | 3.8 ± 0.2             |

**Weighted average: a = 3.80 ± 0.14 cm**

## Requirements
```
matplotlib
astropy
numpy
```

## How to Run
1. Clone the repository
2. Ensure `Braggs_Law.csv` is in the same directory as the notebook
3. Open `Bragg's_Law_Lab.ipynb` in Jupyter Notebook or upload to Google Colab
4. Run all cells
