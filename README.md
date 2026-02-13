# GNSS Signal & AI Modelling – MORP (20 Jan 2026)

This project analyses GPS-only RINEX 2.11 data from station MORP
(downloaded from NASA CDDIS) and applies data-driven techniques
to model GNSS signal instability.

## Objectives
- Parse RINEX observation data using Python (georinex)
- Analyse satellite visibility and signal strength
- Estimate dual-frequency ionospheric behaviour
- Define GNSS noise metrics
- Train a machine learning model to predict signal variability

## Dataset
- Station: MORP
- Date: 20 January 2026 (Day 020)
- Format: RINEX 2.11
- Sampling interval: 30 seconds
- System: GPS only

Raw RINEX files are not included due to file size.
They can be downloaded from NASA CDDIS:

https://cddis.nasa.gov/archive/gnss/data/daily/2026/020/

## Methods
- Pseudorange analysis (C1, C2)
- Signal-to-noise ratio analysis (S1)
- Ionospheric dual-frequency modelling
- Random Forest regression for noise prediction

## Key Results
The model demonstrates that GNSS signal variability
can be predicted using satellite availability,
signal strength, and dual-frequency behaviour.

## Technologies Used
- Python
- georinex
- numpy
- pandas
- matplotlib
- scikit-learn

---

This project demonstrates the integration of GNSS physics
and machine learning techniques, forming a foundation
for Geospatial Artificial Intelligence research.

