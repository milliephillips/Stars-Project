# Stars-Project
Analysis of stars in the 47 Tuc globular cluster using Gaia data.

# Stars Project – 47 Tuc Globular Cluster Analysis

This project analyzes a set of stars within the globular cluster **47 Tuc** using data from the Gaia mission.

## Data
Two datasets were used:
- `47tuc_positions.csv`: Star ID, Right Ascension, Declination, estimated distance from Earth.
- `47tuc_gaia_data.csv`: Star ID, RA/Dec, apparent magnitude, (B – R) colour, proper motion.

The datasets were merged and cleaned to focus on stars within the cluster.

## Analysis & Methods
- Plotted **RA vs Dec** to estimate the cluster radius.
- Created a **colour-magnitude diagram** (apparent and absolute magnitudes) to visualize stellar properties.
- Constructed an **H-R diagram** with effective temperature vs luminosity, and radius color-coded.
- Calculated stellar radii in solar units.
- Techniques used: Python, Pandas, Matplotlib, NumPy.

## Key Findings
- Cluster radius estimated at ~0.758°, matching published data.
- Colour-magnitude and H-R diagrams reveal stellar distribution and evolutionary stages.
- Demonstrates data cleaning, merging, and astrophysical visualization skills.
