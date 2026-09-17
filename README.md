# Vertical_Structure_Evolution_of_LargeSMHWs
This repository contains the codes for the manuscript title "Vertical Structure and Evolution of Large-Scale Subsurface Marine Heatwaves".

There are 5 materials:
1. KNNsmooth.ipynb – Script for smoothing your raw 3D (latitude, longitude and depth) MHW binary mask snapshots at each time step using a standard cube.
2. sMHWmask_0to1month_1993.2020.nc – Example output after KNNsmoothing. This file contains the smoothed 3D MHW masks for January and February 1993 (2 months). It is also input for tracking.
3. Tracking.ipynb – Script for tracking 4D MHWs over time.
4. No.0.MHWmetrics_from_0_to_2months_1993Jan.2020Dece.xlsx - Example of characteristic file of a single MHW event (ID=0). It is input for depth rescaling.
5. depth-rescaling.ipynb - Script showing how to apply depth-recsaling approach onto MHW profiles of each individual mhw event.
