# Inflammatory biomarkers before and after the COVID-19 pandemic — analysis code

This repository contains the analytical code underlying the manuscript on inflammatory biomarker profiles in population-based adult samples from Geneva before (2019) and after (2023–2024) the COVID-19 pandemic.

## Contents

- `Main_Code.ipynb`: cleaned analysis notebook containing only analyses reported in the manuscript and supplementary material.
- `requirements.txt`: Python packages required to run the notebook.
- `.gitignore`: prevents restricted data and generated outputs from being committed accidentally.

## Data

Individual-level Bus Santé data are **not included** in this repository because participant consent does not authorize unrestricted public sharing.

To run the notebook, place the analytical dataset at:

`Data/11_06_biomarker_metafile_for_python.csv`

or edit `DATA_PATH` in the first code cell.

## Analyses reproduced

1. Table 1 — participant characteristics by pandemic period
2. Table S1 — crude biomarker distributions by period and year
3. Figure 1 — semester-specific biomarker trajectories
4. Figure 2 — adjusted pre/post-pandemic biomarker differences
5. Table S2 — sequential regression models
6. Table S3 — year-specific adjusted differences
7. Table S4 — principal component analysis
8. Table S5 — lifestyle–biomarker associations
9. Table S6 / Figure 3 — lifestyle-stratified pre/post-pandemic differences and interaction tests

## Running the analysis

Create a Python environment, install dependencies, open the notebook, then use **Restart Kernel and Run All**. Generated tables are written to `Data/results/` and figures to `Data/figures/`.


## Data availability

Individual-level data from the Bus Santé study are not included in this repository because participants’ informed consent does not permit unrestricted public sharing. Access may be requested from the study investigators following the procedure described in the manuscript.
