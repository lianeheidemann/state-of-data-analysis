# 📊 State of Data Brazil 2023 — Data Market Analysis

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Data%20Analysis-EDA-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%26%20Seaborn-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-orange?style=for-the-badge&logo=jupyter"/>
</p>

An exploratory analysis of the **State of Data Brazil 2023** dataset, focused on the profiles of data professionals in Brazil.

---

## Analysis Pipeline

- Import and inspect the CSV dataset
- Handle missing and inconsistent values
- Rename and standardize columns
- Filter data and create analytical subsets
- Visualize distributions and comparisons
- Extract insights

---

## Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run

```bash
pip install -r requirements.txt
```

To reproduce the complete development environment with pinned transitive dependencies, use the lock file generated with [uv](https://docs.astral.sh/uv/):

```bash
pip install -r requirements-lock.txt
```

> If multiple Python installations are available, use the same interpreter to install dependencies and run the notebook kernel. In VS Code, choose it through **Select Kernel**.

Download the dataset by following [data/README.md](data/README.md), then run [analise_state_of_data_br_2023.ipynb](analise_state_of_data_br_2023.ipynb).

---

## Key Visualizations

### Age Distribution by Gender and Role

<p align="center">
  <img width="996" height="548" alt="Age distribution by role and gender" src="assets/distribuicao_idade_genero.png" />
</p>

### Age Distribution by Race/Ethnicity and Role

<p align="center">
  <img width="996" height="548" alt="Age distribution by role and self-reported race or ethnicity" src="assets/distribuicao_idade_etnia.png" />
</p>

---

## Key Insights

- **Data Science represents the largest analyzed group:** the gender summary contains 535 data scientists, compared with 120 data analysts and 117 data engineers.
- **Women are underrepresented in all three roles:** approximately 17.4% in Data Science, 20.8% in Data Analysis, and 20.5% in Data Engineering.
- **Average ages are similar across genders:** within each role, the observed difference does not exceed 0.8 years; averages range from 34.4 to 36.3 years.
- **Representation by race and ethnicity is uneven:** white respondents form the majority in all three groups. The summary contains only one Indigenous respondent, in Data Engineering, indicating limited representation in the sample.

> These results describe only the selected subset of the **State of Data Brazil 2023** survey. Because the survey is observational and some groups contain few responses, the results do not establish causes or support conclusions about professional retention.

---

## Processed Data and Summary Tables

The notebook exports the processed DataFrames and summary tables used in the analysis to `data/processed/`. This directory is not versioned; its files are generated locally whenever the notebook runs.

---

<p align="center">Developed by <strong>Liane Heidemann</strong></p>
