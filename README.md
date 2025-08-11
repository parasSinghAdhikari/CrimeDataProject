# Crime Data Analysis and Visualization

## 📌 Overview
This project focuses on **Exploratory Data Analysis (EDA)**, **data cleaning**, and **visualization** of crime data.  
It aims to detect missing or inconsistent data, apply intelligent imputation techniques, and present insightful visualizations for better understanding of crime trends.

The workflow is implemented in **Python** using Jupyter Notebooks.

---

## 📂 Project Structure
- **EDA.ipynb** — Performs exploratory data analysis to understand dataset structure, detect missing values, duplicates, and anomalies.
- **CrimeDataAnalysis.ipynb** — Cleans and preprocesses the dataset, filling missing values using reference mappings and statistical approaches.
- **CrimeDataVisualization.ipynb** — Creates various visualizations (charts, maps, and plots) to display crime patterns.

---

## 🛠 Technologies Used
- **Python**
- **Pandas** — Data cleaning & manipulation
- **NumPy** — Numerical computations
- **Matplotlib / Seaborn** — Data visualization
- **Jupyter Notebook** — Interactive development
- **Random module** — Randomized imputation for certain missing values

---

## 🔍 Key Features
- Removal of duplicates and irrelevant rows
- Intelligent missing value filling using:
  - Mapping relationships between **Street**, **Latitude/Longitude**, **District**, and **Reporting Area**
  - Geographical cross-referencing
  - Random sampling within matched clusters
- Filtering of incomplete and inconsistent records
- Export of cleaned dataset to `crimeDataEDA.csv`
- Visualizations for:
  - Crime distribution by district
  - Geospatial mapping of incidents
  - Trends over time

---

## 📊 Dataset
The dataset (`crimeData.csv`) contains:
- **INCIDENT_NUMBER**
- **DISTRICT**
- **REPORTING_AREA**
- **STREET**
- **Lat / Long**
- Additional crime-specific details

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/crime-data-analysis.git
   cd crime-data-analysis
