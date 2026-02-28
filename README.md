# FLOT Chemotherapy Audit - York 2024

## Project Overview
This repository contains the computational analysis for a service evaluation of preoperative FLOT chemotherapy delivery at York Hospital (Jan-Dec 2024). The audit focuses on cycle completion rates, Relative Dose Intensity (RDI), and Lean Body Mass (LBM) changes.

## Methodology: Human-in-the-Loop
This audit utilized a "Human-in-the-Loop" workflow.
1.  **Clinical Oversight:** Audit parameters, data structuring, and validation were performed by the Principal Investigator.
2.  **Computational Assistance:** Python code for biometrics (LBM formula), RDI calculations, and survival analysis (Kaplan-Meier) was generated and verified with assistance from a Large Language Model (Gemini 1.5 Pro).
3.  **Data Governance:** All data is anonymized and processed locally to ensure patient confidentiality.

## Files
- `FLOT_audit.ipynb`: The Jupyter Notebook containing the data, calculations, and visualizations.
