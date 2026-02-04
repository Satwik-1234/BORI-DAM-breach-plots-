# 🏗️ Dam Breach & Release Hydrograph Analysis

## **Kurnur (BORI) Dam, Solapur District, Maharashtra**

---

## 1. Introduction

This repository documents the **hydraulic time‑series analysis and visualization** of dam breach and release scenarios for **Kurnur (BORI) Dam**, Maharashtra.

The work is intended to support:

* Dam Break Analysis (DBA)
* Emergency Action Plan (EAP) preparation
* Technical review by CWC / SDSO / State Dam Safety authorities

The focus of this repository is **engineering‑grade hydrograph plotting** using Python, ensuring accuracy, clarity, and reproducibility.

---

## 2. Study Area

* **Dam Name:** Kurnur (BORI) Dam
* **District:** Solapur
* **State:** Maharashtra, India
* **Type of Analysis:** Dam breach & controlled release hydrographs

---

## 3. Scenarios Analyzed

The following scenarios are covered:

1. **Piping Failure**

   * Progressive internal erosion leading to breach formation

2. **Overtopping Failure**

   * Breach initiation due to reservoir level exceeding dam crest

3. **Large Controlled Release**

   * Non‑failure operational release through gates/spillway

Each scenario is processed independently to avoid analytical ambiguity.

---

## 4. Data

### 4.1 Data Source

* Time‑series outputs exported from **hydraulic / dam‑break modeling software** (e.g., HEC‑RAS)
* Data stored in **Excel (.xlsx)** format

### 4.2 Data Files

Typical datasets include:

* Headwater Elevation (m)
* Tailwater Elevation (m)
* Total Discharge (m³/s)
* Breach Discharge (m³/s) *(where applicable)*
* Breach Width (m) *(separate analysis)*
* Breach Velocity (m/s) *(separate analysis)*

Each Excel file represents **one scenario only** to preserve traceability.

### 4.3 Time Resolution

* Uniform time‑step (typically 5 minutes)
* Time zone as provided by the hydraulic model output

---

## 5. Tools & Software

The analysis is carried out using open‑source scientific tools:

* **Python 3.x**
* **Pandas** – time‑series data handling
* **Matplotlib** – high‑resolution static engineering plots
* **Plotly** – interactive technical visualizations
* **Jupyter Notebook / Google Colab** – execution environment

---

## 6. Methodology

### 6.1 Data Processing

1. Import Excel time‑series data
2. Parse date‑time into Python datetime format
3. Verify units and column consistency
4. No smoothing or artificial modification applied

### 6.2 Plotting Philosophy

* **Dual‑axis hydrographs**:

  * Left Y‑axis → Elevation (m)
  * Right Y‑axis → Discharge (m³/s)

* **Consistent color convention**:

  * Headwater Elevation → Navy Blue
  * Tailwater Elevation → Light Blue
  * Total Discharge → Dark Green (dashed)

* **Engineering‑readable formatting**:

  * Clear axis labels
  * Proper tick spacing
  * One‑line legends

### 6.3 Scenario Separation

* Piping, overtopping, and controlled release plots are generated **independently**
* Breach width and velocity are plotted in **separate dedicated graphs**

---

## 7. Outputs

For each scenario, the following outputs are produced:

### 7.1 Matplotlib Outputs (Static)

* Publication‑quality PNG images
* Suitable for:

  * DBA reports
  * Annexures
  * Regulatory submissions

### 7.2 Plotly Outputs (Interactive)

* Interactive HTML graphs
* Features:

  * Zoom & pan
  * Hover inspection of values
* Suitable for:

  * Technical reviews
  * Presentations

### 7.3 Output Files

* Combined hydrographs (Elevation + Discharge)
* Separate plots for:

  * Breach width vs time
  * Breach velocity vs time

---

## 8. Repository Usage (Beginner Friendly)

1. Upload Excel input files
2. Open the corresponding Jupyter Notebook
3. Run cells sequentially
4. Generated plots will appear inline and/or be saved as image files

No prior GitHub or advanced Python experience is required.

---

## 9. Limitations

* Results depend entirely on input hydraulic model accuracy
* No calibration or field validation is performed within this repository
* Plots represent **post‑processing only**, not model simulation

---

## 10. References

1. Central Water Commission (CWC) – Guidelines for Dam Break Analysis
2. FEMA (2014). *Federal Guidelines for Dam Safety – Dam Breach Analysis*
3. USACE (2021). *HEC‑RAS User Manual*
4. ICOLD Bulletins on Dam Safety and Breach Analysis

---

## 11. Author

**Satwik Udupi**
Agricultural Engineer | Hydrology & GIS
Specialization:

* Dam Break Analysis
* HEC‑RAS 1D/2D
* Hydraulic Modeling & Visualization

---

## 12. Disclaimer

This repository is intended **solely for technical, academic, and professional use**.
The author assumes no liability for regulatory or design decisions made using this material.
