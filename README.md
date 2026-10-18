# Spatial Data Science & Predictive Modeling Pipeline
An advanced analytics repository mapping spatial statistics, time-series distributions, and machine learning pipelines inside ArcGIS Pro.

## Core Algorithmic Implementations & Visual Assets

### 1. Forest-Based Classification & Regression (Random Forest)
- **Tool Executed:** Forest-based Classification and Regression (Spatial Statistics Tools)
- **Execution Run-Time:** 2 Minutes 21 Seconds Flat
- **Model Efficiency:** Training R-Squared: 0.8740 | Validation R-Squared: 0.7320
- **Objective:** Implemented random forest decision-tree algorithms across regional vector maps to establish predictive modeling diagnostics.

![Random Forest Diagnostics](1_random_forest_diagnostics.jpeg)
![Regression Validation Table](2_regression_validation_table.jpeg)

### 2. Explanatory Variable Range Analytics
- **Variables Evaluated:** 2022 Median Age | 2022 Per Capita Income
- **Objective:** Tracked strict minimum and maximum data threshold overlaps to validate model data integrity and eliminate spatial auto-correlation.

![Explanatory Variable Diagnostics](3_explanatory_variable_diagnostics.jpeg)

### 3. Statistical Validation Charts
- **Validation R2 Histogram:** Captures model accuracy distribution variance showing a calculated Mean of 0.49312 and a Median of 0.49363.
- **Per Capita Income Distribution:** Displays a balanced spatial frequency distribution tracking regional economic density across the US mainland.

![Validation R2 Histogram](4_validation_r2_histogram.jpeg)
![Per Capita Income Distribution](5_per_capita_income_distribution.jpeg)

### 4. Data Management & Spatial Join Pipelines
- **Tools Run:** Join Field | Calculate Field (Data Management Tools)
- **Script Expression Language:** Inline PYTHON3
- **Objective:** Executed database merges linking tabular results (`CountyPresElect`) to geometric map records via unified FIPS keys, running custom field equations to clean attribute anomalies.

![Geoprocessing Join Field Log](6_geoprocessing_join_field_log.jpeg)
![Python Calculate Field Script](7_python_calcualte_field_script.jpeg)

### 5. Longitudinal Time-Series Simulation 
- **Temporal Constraints:** 144-Month Step Intervals (Timeline: 2008–2020)
- **Objective:** Programmed a live animated time-slider matrix tracking shifting demographic gradients sequentially across continental US countymaps.

https://github.com/user-attachments/assets/f8c82ac7-cfa2-4345-835d-1799ddedf609

---
### 🐧 Phase 1: Linux Command-Line Telemetry Ingestion (WSL)
Before feeding environmental vectors into the predictive machine learning models, raw crisis streams are processed inside a native Ubuntu Linux terminal framework. 

The localized dataset `crisis_telemetry.csv` tracks automated hazard logs across primary sectors (Tana-River, Kisumu-Transit, Homa-Bay). The ingestion pipeline executes high-velocity micro-filtering using elite command-line utilities:
* **Vector Extraction (`grep`):** Isolates high-priority dynamic lines matching specific crisis criteria.
* **Schema Restructuring (`awk`):** Filters non-essential string fields to map regions directly to their vulnerability scores.
* **Descending Index Ranking (`sort`):** Ranks regional risk metrics to force the highest hazard parameters to the top of the processing ledger for real-time asset allocation.

## Advanced Spatial Statistics & Pattern Detection

*   **Milestone 1: Hot Spot Analysis (Getis-Ord Gi*)**
    *   **Execution Parameters:** Fixed Distance Band scale calibration set precisely to `145772.3786` meters with a False Discovery Rate (FDR) statistical correction applied.
    *   **Analytical Impact:** Eliminated descriptive data assumptions by establishing statistically validated high-confidence (95% to 99% CI) hotspot clusters of infrastructure/social anomalies.
    *   **Artifact Verified:** `Optimized_hotspot_FDR_calibration.jpeg`

*   **Milestone 2: Spatial Outlier Analysis (Anselin Local Moran's I)**
    *   **Execution Parameters:** Contiguity Edges and Corners neighborhood matrix configuration evaluating spatial variance across adjacent boundaries.
    *   **Analytical Impact:** Isolate core spatial anomalies rather than uniform clusters. Programmatically extracted High-Low and Low-High outliers, identifying localized data anomalies critical for resource targeting in Disaster Management environments.
    *   **Artifact Verified:** `Anselin_Local_Morans_I_Outliers.jpeg`

---
### 📫 Enterprise Allocations & Consulting Contracts
To deploy, scale, or integrate this automated predictive AI pipeline for your organization, retain my systems engineering stack directly through [My Upwork Console](https://www.upwork.com/freelancers/~014e56546866817167?mp_source=share).
