# QWZ Chern-Insulator Hamiltonian (Reference Form)

**ID:** `eq-paper1-qwz-hamiltonian`  
**Tier:** derived  
**Score:** 94  
**Units:** OK  
**Theory:** PASS  

## Equation

$$
H(\mathbf{k})=\sin k_x\,\sigma_x+\sin k_y\,\sigma_y+\big(u+\cos k_x+\cos k_y\big)\sigma_z
$$

## Description

The canonical 2D Chern insulator (Qi–Wu–Zhang). In Step 2, the simulator realizes the real-space version with open boundaries and a time-dependent effective mass u_eff(t). Fully validated via FHS lattice Chern number in multiple tools.

## Assumptions

- Two-band model on square lattice with nearest-neighbor hopping.
- Topological phases at C=±1 for −2<u<0 and 0<u<2; trivial otherwise.
- Real-space version uses tight-binding Hamiltonian with same band structure.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*
