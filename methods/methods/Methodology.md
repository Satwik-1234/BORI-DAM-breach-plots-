# Methodology – Dam Breach & Release Hydrograph Analysis

## 1. Objective
To visualize and interpret hydraulic time-series outputs generated from dam breach and controlled release simulations for Kurnur (BORI) Dam.

## 2. Input Data
- Time-series data exported from hydraulic model simulations
- Data format: Excel (.xlsx)
- Parameters include:
  - Headwater elevation (m)
  - Tailwater elevation (m)
  - Total discharge (m³/s)
  - Breach width and velocity (where applicable)

## 3. Data Processing
- Raw model outputs are imported without modification
- Date–time values are parsed into standard datetime format
- No smoothing, filtering, or interpolation is applied

## 4. Plotting Approach
- Dual-axis hydrographs are used:
  - Left axis: Elevation (m)
  - Right axis: Discharge (m³/s)
- Separate plots are generated for:
  - Piping failure
  - Overtopping failure
  - Large controlled release
- Breach width and velocity are plotted independently

## 5. Limitations
- Analysis accuracy depends on hydraulic model quality
- No calibration or validation is performed at this stage
