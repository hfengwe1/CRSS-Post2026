## CRSS Post-2026 Operational Alternatives

This repository contains the RiverWare model files used to evaluate the Colorado River Simulation System (CRSS) post-2026 operational alternatives.

Each `.mdl` file represents a specific alternative:

- **NAA** – No Action Alternative
- **FAA** – Federal Authorities Alternative
- **FAHA** – Federal Authorities Hybrid Alternative
- **CCA** – Cooperative Conservation Alternative
- **BHA** – Basin Hybrid Alternative

The policy rules and operating logic for each alternative are embedded within the corresponding RiverWare model file. No separate policy files are provided.

## Synthetic Traces

The repository also contains a compressed archive of synthetic hydrology traces used in the CRSS post-2026 alternative evaluations.

## Figures

The repository includes Python notebooks used to process model outputs and generate figures.

- `FullOrganizedPlots_R1.ipynb` – Processes and organizes simulation results, including renaming variables, combining outputs from multiple alternatives, and converting monthly data to annual values.

- `FinalFigure_Conserve_r1.ipynb` – Generates the figures and visualizations used for the analysis and comparison of post-2026 operational alternatives.
