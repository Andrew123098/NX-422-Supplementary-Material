# Thin-Film Electrode for Dorsal Root Ganglion Stimulation

This repository contains MATLAB files and associated resources for the computational design and feasibility assessment of a biocompatible thin-film electrode targeting the dorsal root ganglion (DRG). The project aims to address phantom limb pain (PLP) in lower-limb amputees by leveraging the unique properties of DRG stimulation.

## Project Overview

Amputation often results in complications like impaired balance, reduced gait stability, and phantom limb pain. While existing therapies can mitigate some symptoms, severe cases of PLP often require spinal cord stimulation (SCS). This project proposes a novel thin-film electrode design for DRG stimulation, which offers several benefits:

- **Improved Conformity:** The flexible thin-film electrode adheres better to the dura mater for long-term implantation.
- **Targeted Stimulation:** DRG stimulation is effective at low-frequency, low-amplitude levels and avoids the paresthesia commonly associated with dorsal column stimulation.
- **Potential for Enhanced Outcomes:** DRG stimulation reduces PLP without triggering paresthesia and may improve gait stability and balance control.

This repository provides the detailed computational work supporting the electrode design, including strain analysis, material selection, and neutral plane calculations.

## Repository Contents

- **`strain_analysis.m`**: MATLAB script for computing strains at various layers of the electrode structure and comparing them to critical strain limits for each material.
- **`neutral_plane_calculation.m`**: MATLAB script for calculating the neutral plane of the multi-layered thin-film electrode.
- **`gold_tmp_vs_resistivity.mat`**: Data file containing the relationship between gold resistivity and temperature, used in interconnect design.
- **Supporting Materials**: Additional documentation and figures referenced in the calculations.

## Key Features

- **Material Analysis:** Ensures all materials operate below their critical strain thresholds.
- **Neutral Plane Optimization:** Calculates the mechanical stress distribution across the multi-layered structure.
- **Electrical Properties:** Includes analysis of gold interconnects' resistivity at physiological temperatures.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/thin-film-electrode
2. Open the MATLAB scripts in your MATLAB environment.
3. Run the scripts to reproduce strain calculations and material analysis.

## License

This repository is distributed under the [MIT License](LICENSE).

## Contact

For questions or feedback, please contact andrew.brown@epfl.ch.
