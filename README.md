# Vertical_Structure_Evolution_of_LargeSMHWs

This repository contains the code and example input files associated with the manuscript **“Vertical Structure and Evolution of Large-Scale Subsurface Marine Heatwaves”**.

The repository includes the following materials:

- **KNNsmooth.ipynb**: Applies KNN-based smoothing to raw 3D (latitude, longitude, and depth) MHW binary-mask snapshots at each time step using a standard cube.
- **Tracking.ipynb**: Tracks the 4D (latitude, longitude, depth, and time) evolution of individual MHW events.
- **No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx**: Example characteristic file for a single MHW event (ID = 0), used as input for the subsequent depth-rescaling, vertical-structure clustering, and 2D rescaling and clustering steps.
- **depth-rescaling.ipynb**: Applies the depth-rescaling approach to the MHW profiles of individual events.
- **vertical_structure_clustering.ipynb**: Applies one-dimensional agglomerative clustering to randomly selected MHW profiles from all events to identify distinct vertical structure types.
- **2D_rescaling_and_clustering.ipynb**: Applies two-dimensional (depth–time) rescaling and clustering to MHW profiles at the persistence centres of all events to identify distinct vertical evolution types.


## Workflow

Run the notebooks in the following order:
KNNsmooth.ipynb -> Tracking.ipynb -> depth-rescaling.ipynb -> vertical_structure_clustering.ipynb -> 2D_rescaling_and_clustering.ipynb
