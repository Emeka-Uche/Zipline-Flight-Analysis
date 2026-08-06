# Zipline-Flight-Analysis
End-to-end analytics case study analyzing Zipline flight operations. Includes executive KPI recommendations, data visualizations, and root cause investigation of a failed flight using exploratory data analysis and supporting charts.


## Repository Contents

| Folder | Description |
|---------|-------------|
| data | Raw datasets provided for the case study |
| notebooks | Jupyter notebooks containing the complete analysis |
| reports | Written responses and executive summaries |


## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib


# Project Overview

The case study consists of two analytical tasks.

## Part 1. Executive Flight Metrics

Identify a small set of operational metrics that would help Zipline executives monitor business performance.

The analysis includes:

- Data exploration and cleaning
- Feature engineering
- KPI development
- Executive visualizations
- Business interpretation
- Data quality assessment

### Notebook

`notebooks/01_Executive_Metrics_Analysis.ipynb`

### Executive Summary

`reports/Question_1_Metrics.md`

### Dashboard Summary

`reports/Question_2_Summary.md`

---


## Part 2. Failed Flight Investigation

Analyze telemetry collected from a failed aircraft flight to determine:

- When the failure began
- What system failed
- Evidence supporting the diagnosis
- Probable root cause
- Recommendations for engineering investigation

The analysis includes time-series visualization of telemetry data and identification of abnormal system behavior leading up to the failure.

### Notebook

`notebooks/02_Failed_Flight_Investigation.ipynb`

### Investigation Report

`reports/Failed_Flight_Summary.md`

---
