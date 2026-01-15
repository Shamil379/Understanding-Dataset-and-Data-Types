# Exploratory Data Analysis (EDA)
## Titanic Dataset & Student Performance Dataset

## 📌 Project Overview
This repository contains an exploratory data analysis (EDA) of two real-world datasets:

- **Titanic Dataset**
- **Student Performance Dataset**

The objective of this project is to understand the structure, feature types, data quality, and machine learning suitability of both datasets using Python and Jupyter Notebook.

---

## 📂 Repository Contents
- `EDA_Titanic_Student_Performance.ipynb`  
  Jupyter Notebook containing complete exploratory data analysis, observations, and a one-page data analysis report.

- `Titanic-Dataset.csv`  
  Dataset containing passenger information from the Titanic.

- `student_data.csv`  
  Dataset containing student demographic and academic performance data.

- `README.md`  
  Project documentation.

---

## 🛠️ Tasks Performed
The following steps were carried out for **both datasets**:

1. Loaded datasets using **Pandas**
2. Displayed first and last records to understand structure
3. Manually identified:
   - Numerical features
   - Categorical features
   - Ordinal features
   - Binary features
4. Used `df.info()` to inspect data types and missing values
5. Used `df.describe()` for statistical summaries
6. Analyzed unique values in categorical columns
7. Identified target variables and input features for machine learning
8. Analyzed dataset size and suitability for ML tasks
9. Documented data quality issues such as missing values and imbalance
10. Prepared a **one-page data analysis report**

---

## 🎯 Target Variables
- **Titanic Dataset:** `Survived` (Binary Classification)
- **Student Performance Dataset:** `G3` (Final Grade – Regression or Classification)

---

## 🤖 Machine Learning Suitability
- **Titanic Dataset**
  - Suitable for binary classification
  - Requires preprocessing (missing values, encoding)
  - Commonly used for ML education and benchmarking

- **Student Performance Dataset**
  - Clean and well-structured
  - Suitable for regression or classification
  - Minimal preprocessing required

---

## ⚠️ Data Quality Observations
- Titanic dataset contains missing values (Age, Cabin) and class imbalance
- Student Performance dataset has no missing values and consistent data

---

## ▶️ How to Run
1. Clone the repository
2. Ensure all files are in the same directory
3. Open the notebook using Jupyter Notebook or JupyterLab
4. Run cells sequentially

---

## 📦 Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ✍️ Author
This project was prepared for academic purposes using Jupyter Notebook to demonstrate exploratory data analysis and machine learning readiness assessment.
