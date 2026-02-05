# 🏗️ Dam Breach & Release Hydrograph Analysis

## **Kurnur (BORI) Dam, Solapur District, Maharashtra**

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Dam%20Safety-red" />
  <img src="https://img.shields.io/badge/Domain-Hydrology-blue" />
  <img src="https://img.shields.io/badge/Analysis-Dam%20Break%20%26%20Hydrographs-orange" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" />
</p>

---

## 📌 Introduction

This repository documents the **hydraulic time-series analysis and visualization** of **dam breach and controlled release scenarios** for **Kurnur (BORI) Dam**, Maharashtra.

The work focuses on **engineering-grade hydrograph plotting** using Python for **accuracy, clarity, traceability, and reproducibility**, and is intended to support:

* **Dam Break Analysis (DBA)**
* **Emergency Action Plan (EAP) preparation**
* **Technical review by CWC / SDSO / State Dam Safety Authorities**
* **Academic and professional hydraulic analysis**

⚠️ *This repository performs post-processing and visualization only; it does not simulate breach hydraulics.*

---

## 📍 Study Area

* **Dam Name:** Kurnur (BORI) Dam
* **District:** Solapur
* **State:** Maharashtra, India
* **Type of Study:**

  * Dam breach hydrographs
  * Large controlled release hydrographs

---

## 🔍 Scenarios Analyzed

Each scenario is processed **independently** to maintain analytical clarity and regulatory traceability.

### 1️⃣ Piping Failure

* Progressive internal erosion
* Breach formation due to piping
* Time-varying discharge, elevation, breach parameters

### 2️⃣ Overtopping Failure

* Reservoir level exceeding dam crest
* Rapid breach initiation
* Peak breach discharge analysis

### 3️⃣ Large Controlled Release

* Non-failure operational release
* Spillway / gate-controlled discharge
* Comparison with breach scenarios

---

## 🧭 Interactive Navigation

### 📂 Data

➡️ **[Data Folder](./data/)**
➡️ **[Data Description](./data/Data_Description.md)**

### 📘 Methodology

➡️ **[Methods Folder](./methods/)**
➡️ **[Methodology & Assumptions](./methods/Methodology_and_Assumptions.md)**

### 📊 Scripts (Core Analysis)

➡️ **[Scripts Folder](./scripts/)**

* Piping breach hydrographs
* Overtopping breach hydrographs
* Large controlled release plots
* Breach width & velocity vs time

### 📈 Outputs

➡️ **[Outputs Folder](./outputs/)**
➡️ **[Output Summary](./outputs/README.md)**

### 📚 References

➡️ **[References Folder](./references/)**
➡️ **[Reference List](./references/References.md)**

---

## 📂 Repository File Structure

```text
.
├── data
│   ├── Large_Controlled_Release_Hydrograph.xlsx
│   ├── Overtopping breach hydrograph.xlsx
│   ├── Piping Breach hydrograph.xlsx
│   ├── Overtopping_Piping_Breach_Parameters.xlsx
│   ├── Data_Description.md
│   └── README.md
│
├── methods
│   ├── Methodology_and_Assumptions.md
│   └── README.md
│
├── scripts
│   ├── Large_controlled_Release_Bori.ipynb
│   ├── Overtopping_breach_Plots_Bori_Dam_.ipynb
│   ├── Piping_breach_graphs_BORI_DAM.ipynb
│   ├── BORI_breach_width_Velovity_time.ipynb
│   └── README.md
│
├── outputs
│   ├── LCR_BORI_Release.png
│   ├── OVTP-BORI-Breach.png
│   ├── PIPG-BORI-Breach.png
│   └── README.md
│
├── references
│   ├── References.md
│   └── README.md
│
├── tools
│   └── README.md
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🛠️ Tools & Software Stack

* **Python 3.x** – core computation
* **Pandas** – time-series handling
* **Matplotlib** – static, publication-quality engineering plots
* **Plotly** – interactive hydrographs
* **Jupyter Notebook / Google Colab** – execution environment

---

## 🧪 Methodology (Summary)

### Data Processing

* Import Excel time-series outputs from hydraulic models (e.g., HEC-RAS)
* Parse date-time fields
* Verify units and column consistency
* No smoothing, interpolation, or artificial modification

### Plotting Philosophy

* **Dual-axis hydrographs**

  * Left Y-axis → Elevation (m)
  * Right Y-axis → Discharge (m³/s)
* Consistent engineering color convention
* Clean legends and axis labels for regulatory submission

### Scenario Isolation

* Piping, overtopping, and controlled release handled separately
* Breach width and velocity plotted independently

---

## 📤 Outputs

### Static Outputs (Matplotlib)

* High-resolution PNG images
* Suitable for:

  * DBA reports
  * Annexures
  * Regulatory submissions

### Interactive Outputs (Plotly)

* Zoom, pan, hover inspection
* Suitable for:

  * Technical review meetings
  * Presentations

---

## ⚠️ Limitations

* Results depend entirely on hydraulic model outputs
* No calibration or field validation included
* Repository performs **post-processing only**

---

## 📚 References

* Central Water Commission (CWC) – Guidelines for Dam Break Analysis
* FEMA (2014) – Federal Guidelines for Dam Safety
* USACE (2021) – HEC-RAS User Manual
* ICOLD Bulletins on Dam Safety

---

## 👤 Author

**Satwik Udupi**
*Agricultural Engineer | Hydrology & GIS Specialization*

**Expertise:**

* Dam Break Analysis
* HEC-RAS 1D / 2D
* Hydraulic Time-Series Visualization

---

## ⚖️ Disclaimer

This repository is intended **solely for technical, academic, and professional use**.
The author assumes **no liability** for regulatory, design, or operational decisions made using this material.


