# 💊 Drug Side Effects Dataset — Data Cleaning & Preprocessing

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?logo=tableau)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi)

## 📌 Project Overview

This project focuses on the **data cleaning and preprocessing** of a synthetic Drug Side Effects dataset containing **100,000 records and 16 columns**.

The dataset was obtained from **Kaggle** and processed using **Python, Pandas, and NumPy in Google Colab**.

The main objective was to identify data-quality issues, clean and transform the dataset, validate the results, and prepare an analysis-ready dataset for further visualization and dashboard development using **Tableau and Power BI**.

---

## 🎯 Objectives

The main objectives of this project are:

- Inspect the original dataset and understand its structure
- Identify missing values
- Check for duplicate records
- Identify and correct inappropriate data types
- Convert date columns into datetime format
- Handle missing categorical values
- Handle missing numerical values
- Validate the cleaned dataset
- Export the final cleaned dataset
- Prepare the dataset for Tableau and Power BI dashboards

---

## 📊 Dataset Overview

| Attribute | Details |
|---|---|
| Dataset | Drug Side Effects |
| Source | Kaggle |
| Records | 100,000 |
| Columns | 16 |
| Data Type | Synthetic Healthcare Dataset |
| Environment | Google Colab |
| Programming Language | Python |
| Libraries | Pandas, NumPy |
| Dashboard Tools | Tableau, Power BI |

---

## 🔍 Data Quality Assessment

Initial inspection of the dataset identified missing values in the following columns:

| Column | Missing Values |
|---|---:|
| `chronic_condition` | 16,743 |
| `alcohol_use` | 33,365 |
| `recovery_days` | 11,738 |

The dataset contained **no duplicate records** during the initial quality assessment.

---

## 🧹 Data Cleaning Process

The following steps were performed during preprocessing:

### 1. Import Required Libraries

Python libraries required for data manipulation and numerical operations were imported.

```python
import pandas as pd
import numpy as np

```python
import pandas as pd
import numpy as np
```

### 2. Load the Dataset

Loaded the original CSV dataset into a Pandas DataFrame for inspection and preprocessing.

### 3. Inspect the Dataset

Examined the dataset structure, column names, data types, missing values, and duplicate records.

### 4. Missing Value Analysis

Identified missing values in the `chronic_condition`, `alcohol_use`, and `recovery_days` columns.

### 5. Duplicate Check

Checked the dataset for duplicate records.

**Result:** No duplicate records were found during the initial assessment.

### 6. Date Conversion

Converted the following columns into datetime format:

* `report_date`
* `treatment_start_date`

### 7. Handle Missing Categorical Values

Replaced missing categorical values with `Unknown`.

### 8. Handle Missing Numerical Values

Applied median imputation to missing values in `recovery_days`.

### 9. Export the Cleaned Dataset

Exported the processed dataset as a CSV file for further analysis and visualization.

---

## 📋 Data Cleaning Summary

| Data Quality Issue       | Column                 | Cleaning Method         |
| ------------------------ | ---------------------- | ----------------------- |
| Missing values           | `chronic_condition`    | Replaced with `Unknown` |
| Missing values           | `alcohol_use`          | Replaced with `Unknown` |
| Missing values           | `recovery_days`        | Median imputation       |
| Date datatype conversion | `report_date`          | Converted to datetime   |
| Date datatype conversion | `treatment_start_date` | Converted to datetime   |
| Duplicate records        | Entire dataset         | Checked; none found     |

---

## ✅ Validation

After preprocessing:

* Missing values were addressed.
* Duplicate records remained at zero.
* Date columns were converted to datetime format.
* The processed dataset was prepared for further data analysis and visualization.

---

## 📁 Project Structure

```text
Drug-Side-Effects-Cleaning-Analysis/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── drug_side_effects_100k_dirty.csv
│   │
│   └── cleaned/
│       └── drug_side_effects_100k_cleaned.csv
│
├── notebooks/
│   └── Drug_Side_Effects_Data_Cleaning.ipynb
│
└── report/
    └── Data_Cleaning_Report.pdf
```

*Note: Update the filenames and folder structure to match the files actually uploaded to your repository.*

---

## 🛠️ Tools & Technologies

* **Python** — Data processing
* **Pandas** — Data manipulation and cleaning
* **NumPy** — Numerical operations
* **Google Colab** — Development environment
* **Tableau** — Data visualization
* **Power BI** — Dashboard development
* **GitHub** — Project documentation and version control

---

## 🔄 Data Processing Workflow

```text
Kaggle Dataset
      ↓
Raw / Uncleaned Data
      ↓
Data Inspection
      ↓
Data Quality Assessment
      ↓
Missing Value Treatment
      ↓
Date Conversion
      ↓
Validation
      ↓
Cleaned Dataset
      ↓
Tableau / Power BI Dashboards
```

---

## 🚀 Future Scope

* Develop interactive Tableau and Power BI dashboards.
* Perform exploratory data analysis (EDA).
* Analyze patterns in reported drug side effects.
* Conduct statistical analysis using the cleaned dataset.
* Explore machine learning applications where appropriate.

---

## 📄 Project Report

The project report documents the initial data-quality assessment, data-cleaning methodology, preprocessing steps, validation, and final outcome.

---

## 👩‍💻 Author

**Rubysha E**

III B.Sc. Data Science
PSGR Krishnammal College for Women
Coimbatore, Tamil Nadu, India

---

## ⭐ Project Outcome

This project demonstrates a structured data-cleaning workflow using Python, Pandas, and NumPy. The process addresses missing values, checks for duplicates, converts date columns, and prepares the dataset for subsequent analysis and visualization.

The resulting dataset provides a foundation for healthcare data analytics and dashboard development using Tableau and Power BI.
