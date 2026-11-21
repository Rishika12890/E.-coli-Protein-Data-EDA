# Ecoli Dataset — Exploratory Data Analysis (EDA)

## Project Overview

This project explores the Ecoli dataset using Python. The notebook performs Exploratory Data Analysis (EDA) on numerical measurements related to protein sequences and examines how records are distributed across protein localization classes.

The analysis is carried out using Pandas, NumPy, Matplotlib, and Seaborn.

## Objectives

- Load and inspect the Ecoli dataset.
- Count records in each localization class.
- Calculate descriptive statistics.
- Identify the most common localization class.
- Compare average feature values across classes.
- Find the top 5 records by mcg.
- Check missing values and duplicate rows.
- Create data visualizations.

## Dataset

The project uses two dataset files:

- `ecoli.data`
- `ecoli.names`

### Columns

| Column | Description |
|---|---|
| Sequence_Name | Sequence identifier |
| mcg | Numerical feature |
| gvh | Numerical feature |
| lip | Numerical feature |
| chg | Numerical feature |
| aac | Numerical feature |
| alm1 | Numerical feature |
| alm2 | Numerical feature |
| Class | Protein localization class |

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed

### 1. Dataset Inspection
Loaded the dataset and checked its first and last rows, shape, information, and descriptive statistics.

### 2. Localization Class Counts
Calculated the number of records in each localization class using `value_counts()`.

### 3. Descriptive Statistics
Calculated mean, median, minimum, and maximum values for selected numerical columns.

### 4. Most Common Localization Class
Identified the class with the highest number of records.

### 5. Class-wise Feature Comparison
Compared average mcg and gvh values across different classes.

### 6. Top 5 mcg Records
Displayed the five records with the highest mcg values.

### 7. Data Quality Checks
Checked for missing values and duplicate records.

### 8. Data Visualization
Created:
- Count plot for localization class distribution.
- Histogram for mcg feature distribution.

## How to Run

1. Clone or download this repository.
2. Make sure the notebook and dataset files are available.
3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter# E.-coli-Protein-Data-EDA
