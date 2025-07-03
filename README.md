# NEGF-Based Quantum Transport Simulations

This repository contains simulation notebooks based on the **Non-Equilibrium Green's Function (NEGF)** formalism applied to 1D quantum systems. The goal is to model electron transport under coherent conditions, analyze transmission spectra, and explore quantum effects such as **resonant tunneling**, **negative differential resistance (NDR)**, and **quantum point contacts**.

---

## 📁 Notebooks

| No. | File | Description |
|-----|------|-------------|
| 1 | `1)1DWIRE.ipynb` | Basic current vs voltage simulation in a **ballistic 1D wire** using NEGF formalism. |
| 2 | `2)Point_scatterer_1Dwire.ipynb` | NEGF-based simulation of a **1D wire with a single point scatterer** (barrier potential). |
| 3 | `3)2scatteres_1Dwire.ipynb` | Double-barrier structure showing **resonant tunneling** through two scatterers. |
| 4 | `4)NDR.ipynb` | Demonstration of **Negative Differential Resistance (NDR)** using energy-filtered transmission. |
| 5 | `5)6_scatterers_1Dwire.ipynb` | A series of **6 scatterers in a 1D wire**, analyzing suppression and resonances in transmission. |
| 6 | `6)QuantumPointContact.ipynb` | Simulation of a **Quantum Point Contact (QPC)** showing quantized conductance steps. |

---

## ⚙️ Methods

- **NEGF formalism** (retarded Green's function, self-energies, transmission)
- Coherent transport assumption (low temperature, ballistic regime)
- Discretized tight-binding Hamiltonians
- Energy integration for I–V characteristics using Landauer formula

---

## 🧰 Tools Used

- Python 3.11
- Jupyter Notebooks
- NumPy, SciPy, Matplotlib
- VS Code + Git

---

## 📌 Notes

- Simulations are inspired by lectures and code examples from *"Atom to Transistor"* by Prof. Supriyo Datta.
- Assumes low-temperature regime: `kT ≈ 0.01 × t₀` for sharp transmission features.
- This is an ongoing project — files will be progressively documented, optimized, and expanded.

---

## 📬 Contact

> Siddharth Sinha  
> B.Tech Engineering Physics  
> GitHub: [@Sinha-SiDDharth](https://github.com/Sinha-SiDDharth)
