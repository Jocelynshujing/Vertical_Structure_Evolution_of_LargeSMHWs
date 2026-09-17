# Vertical_Structure_Evolution_of_LargeSMHWs
This repository contains the codes for the manuscript title "Vertical Structure and Evolution of Large-Scale Subsurface Marine Heatwaves".

There are 5 materials:
- "KNNsmooth.ipynb": a script for smoothing our raw 3D (latitude, longitude and depth) MHW binary mask snapshots at each time step using a standard cube.
- "sMHWmask_0to1month_1993.2020.nc": an example output after KNNsmoothing. This file contains the smoothed 3D MHW masks for January and February 1993 (2 months). It is also input for tracking.
- "Tracking.ipynb": a script for tracking 4D (latitude, longitude, depth and time) evolutions of MHW events.
- "No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx": an example of characteristic file of a single MHW event (ID=0). It is input for depth rescaling.
- "depth-rescaling.ipynb": a script for applying depth-recsaling approach onto MHW profiles of each individual mhw event.
