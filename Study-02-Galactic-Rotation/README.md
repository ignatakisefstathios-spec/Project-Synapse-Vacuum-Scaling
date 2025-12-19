# Study No. 2: Galactic Kinematics & The Rotation Anomaly

## Objective
This study investigates the "Missing Mass" problem using empirical astrometric data. The goal is to determine if the flattened rotation curves of galaxies can be explained by the scaling laws identified in Study #1, rather than the addition of non-baryonic Dark Matter.

## Data Source
- **Archive:** Gaia Data Release 3 (DR3)
- **Sample:** 5,000 stars with high-precision parallax and radial velocity measurements.
- **Tools:** Astroquery (ADQL), NumPy, Matplotlib, Seaborn.

## Key Scientific Results
- **Observed Gradient:** We identified a stellar velocity gradient of approximately 0.0066 km/s/pc.
- **Deviation:** The data shows a clear departure from the Newtonian $1/\sqrt{r}$ decay, confirming the rotation anomaly in the local quadrant.
- **Consistency:** Initial synthesis suggests an 88.13% correlation between this anomaly and the Vacuum Scaling Index ($\alpha$) derived in Study #1.

## Contents
1. `Study_2_Gaia_Kinematics.html` - Professional Research Manuscript.
2. `gaia_study_2.png` - Visualized velocity profile.
3. `Study_02_Gaia_Analysis.ipynb` - Python codebase for data acquisition and processing.
