# ML_Task01
# ML_Task01 – Task 1: Understanding Dataset & Data Types (Titanic)

## Objective
Perform exploratory analysis to understand the dataset structure, data types, feature categories, missing values, and ML readiness.

## Dataset
- Titanic Dataset (`Titanic-Dataset.csv`)

## Tools Used
- Google Colab
- Python: Pandas, NumPy

## What I Did
1. Loaded the dataset using Pandas and displayed first/last records.
2. Used `df.info()` to inspect data types and null values.
3. Used `df.describe()` to view statistical summaries of numerical columns.
4. Manually classified features into numerical, categorical, ordinal, and binary.
5. Checked unique values and distributions for categorical columns.
6. Identified the target variable (`Survived`) and discussed ML suitability.
7. Documented data quality issues such as missing values and possible class imbalance.

## Files in this Repository
- `Task1_Titanic_Analysis.ipynb` → Colab notebook with full analysis
- `Titanic-Dataset.csv` → dataset file used
- `report.md` → 1-page dataset analysis report

## How to Run
Open `Task1_Titanic_Analysis.ipynb` in Google Colab or Jupyter Notebook and run cells top to bottom.  
Ensure `Titanic-Dataset.csv` is in the same directory as the notebook (or uploaded in Colab session).
