# Vertical_Structure_Evolution_of_LargeSMHWs

This repository contains the code and example input/output files associated with the manuscript “Vertical Structure and Evolution of Large-Scale Subsurface Marine Heatwaves.”

The repository includes five materials:

- **KNNsmooth.ipynb**: Applies KNN-based smoothing to raw 3D (latitude, longitude, and depth) MHW binary-mask snapshots at each time step using a standard cube.
- **sMHWmask_0to1month_1993.2020.nc**: Example output from the KNN smoothing step, containing smoothed 3D MHW masks for January–February 1993 (2 months). This file is also used as input for the tracking step.
- **Tracking.ipynb**: Tracks the 4D (latitude, longitude, depth, and time) evolution of individual MHW events.
- **No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx**: Example characteristic file for a single MHW event (ID = 0), used as input for the depth-rescaling step.
- **depth-rescaling.ipynb**: Applies the depth-rescaling approach to the MHW profiles of individual MHW events.
