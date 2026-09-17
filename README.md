# Vertical_Structure_Evolution_of_LargeSMHWs

This repository contains the code and example input files associated with the manuscript “Vertical Structure and Evolution of Large-Scale Subsurface Marine Heatwaves.”

The repository includes four materials:

- **KNNsmooth.ipynb**: Applies KNN-based smoothing to raw 3D (latitude, longitude, and depth) MHW binary-mask snapshots at each time step using a standard cube.
- **Tracking.ipynb**: Tracks the 4D (latitude, longitude, depth, and time) evolution of individual MHW events.
- **No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx**: Example characteristic file for a single MHW event (ID = 0), used as input for the depth-rescaling step.
- **depth-rescaling.ipynb**: Applies the depth-rescaling approach to the MHW profiles of individual MHW events.

Here is the order to run the notebooks: 

KNNsmooth.ipynb -> Tracking.ipynb -> depth-rescaling.ipynb + No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx
