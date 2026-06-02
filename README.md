# 🧪 Clinical Trial Data Analysis – Heart Disease Study

## 📌 Project Overview

This project focuses on analysing a clinical-style dataset to identify key factors influencing heart disease outcomes. The goal was to apply data analysis, statistical testing, and visualisation techniques to simulate real-world healthcare and pharmaceutical analytics.

---

## 🎯 Objectives

* Analyse patient-level clinical data to identify patterns and trends
* Evaluate relationships between risk factors and heart disease
* Perform statistical hypothesis testing to validate findings
* Build insights that support data-driven healthcare decision-making

---

## 📂 Dataset

* Source: Public dataset (Heart Disease UCI / Kaggle)
* Records: 1025 patients
* Features: 14 variables including demographic, clinical, and diagnostic attributes

### Key Variables:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Max Heart Rate
* Exercise Induced Angina
* Target (Heart Disease: 1 = Yes, 0 = No)

---

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy)
* SciPy (Statistical Testing)
* Seaborn & Matplotlib (Visualisation)
* Jupyter Notebook
* Power BI / Tableau (Dashboard - optional)

---

## 🔧 Data Preparation

* Checked for missing values (none found)
* Standardised column names
* Converted categorical variables into numerical format using one-hot encoding
* Ensured dataset was suitable for statistical and analytical modelling

---

## 📊 Exploratory Data Analysis

Key analyses performed:

* Distribution of heart disease cases
* Age-based comparison between patient groups
* Cholesterol level comparison across disease categories
* Demographic and clinical trend evaluation

---

## 🧪 Statistical Analysis

A **T-test** was performed to evaluate whether cholesterol levels differ significantly between patients with and without heart disease.

### Results:

* Average Cholesterol (No Disease): **251.29**
* Average Cholesterol (Disease): **240.98**
* p-value: **0.00135**

### Interpretation:

The p-value (< 0.05) indicates a **statistically significant difference** between the two groups.

---

## 💡 Key Insights

* Cholesterol levels differed significantly between patient groups
* The observed trend was **counterintuitive**, with lower cholesterol in patients with heart disease
* This suggests that cholesterol alone may not be a strong predictor
* Highlights the importance of **multivariate analysis in healthcare data**

---

## 📈 Visualisations

The following visualisations were created:

* Bar chart comparing cholesterol levels by disease status
* Age distribution across patient groups
* Correlation heatmap of clinical variables

---

## 🧠 Business / Healthcare Impact

* Demonstrates how statistical analysis can support clinical decision-making
* Highlights importance of validating assumptions using data
* Provides a foundation for predictive modelling in healthcare
* Applicable to pharmaceutical research and patient risk analysis

---

## 🚀 Future Improvements

* Apply machine learning models (Logistic Regression, Random Forest)
* Perform multivariate analysis for deeper insights
* Expand dataset for improved generalisation
* Integrate real-world clinical datasets

---

## 📌 Conclusion

This project demonstrates the application of data analytics and statistical techniques in a healthcare context. It highlights the importance of data validation, hypothesis testing, and critical thinking in deriving meaningful insights from clinical data.

---

## 🔗 Author

**Aasim Inamdar**
Data Analyst | Healthcare & Pharma Analytics
Dublin, Ireland
