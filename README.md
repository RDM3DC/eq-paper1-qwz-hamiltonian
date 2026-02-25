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

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id eq-paper1-qwz-hamiltonian --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
