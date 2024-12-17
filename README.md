# Thin-Film Electrode for Dorsal Root Ganglion Stimulation

This repository contains MATLAB files and associated resources for the computational design and feasibility assessment of a biocompatible thin-film electrode targeting the dorsal root ganglion (DRG). The project aims to address phantom limb pain (PLP) in lower-limb amputees by leveraging the unique properties of DRG stimulation.

## Repository Contents

- **`Project_Calculations.mlx`**: MATLAB live script for all calculations for material and electrical properties and analysis.
- **`gold_tmp_vs_resistivity.mat`**: Data file containing the relationship between gold resistivity and temperature, used in interconnect design.
- **`shannon_limit.ipynb**`: Jupyter notebook file used to produce Figure 5 in the report. Requires `seaborn`, `numpy` and `matplotlib`.

## Key Features

- **Material Analysis:** Ensures all materials operate below their critical strain thresholds.
- **Electrical Properties:** Includes analysis of gold interconnects' resistivity at physiological temperatures.
- **Shannon Limit** Makes sure that our device does not exceed the safety threshold for neurostimulation.

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
