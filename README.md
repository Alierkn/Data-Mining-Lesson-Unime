# Data Mining & Analysis - University Learning Resource

[![CI](https://github.com/Alierkn/Data-Mining-Lesson-Unime/actions/workflows/ci.yml/badge.svg)](https://github.com/Alierkn/Data-Mining-Lesson-Unime/actions/workflows/ci.yml)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-notebooks-F37626.svg)](notebooks/)

## 📖 Course Overview

**Data-Mining-Lesson-Unime** is a complete, professional-grade learning resource for mastering data mining and analysis techniques. This course covers the entire data science pipeline from raw data to trained models.

### 🎯 Who This Course Is For

- Students learning data mining and analysis
- Data science beginners wanting hands-on practice
- Anyone preparing for data mining exams
- Professionals looking to brush up on fundamentals

---

## 📚 Course Structure

### **Lecture 1 - Data Exploration (NB1)** - 2 hours
**Concepts:** Attribute classification, statistics, visualization, correlation
**Dataset:** Titanic (891 observations)

Learn to:
- Classify data as Nominal, Ordinal, Interval, or Ratio
- Compute statistical measures (mean, median, variance, IQR)
- Visualize distributions using histograms, boxplots, and KDE
- Analyze correlations between features
- Assess data quality

### **Lecture 2 - Data Cleaning (NB2)** - 2.5 hours
**Concepts:** Missing values, outliers, scaling, encoding
**Dataset:** Titanic (with deliberate errors)

Learn to:
- Remove duplicates and handle missing values (MCAR, MAR, MNAR)
- Apply imputation strategies (mean, median, mode, conditional)
- Detect and treat outliers (IQR method, Z-score method)
- Understand normalization vs standardization
- Encode categorical variables (Label Encoding, One-Hot Encoding)

### **Lecture 3 - Linear Regression & Gradient Descent (NB3)** - 3 hours
**Concepts:** Regression from scratch, optimization algorithms
**Dataset:** California Housing (20,640 observations)

Learn to:
- Build a Linear Regression model from scratch
- Implement Gradient Descent algorithm step-by-step
- Understand cost functions (MSE) and gradients
- Experiment with learning rates and convergence
- Evaluate models using multiple metrics (MSE, RMSE, MAE, R²)

### **Lecture 4 - Capstone Project (NB4)** - 2.5 hours
**Concepts:** End-to-end pipeline, real-world application
**Dataset:** California Housing (full project)

Learn to:
- Apply all L1-L3 concepts in sequence
- Execute a complete data mining pipeline
- Analyze residuals and feature importance
- Write professional findings and conclusions

---

## 🗂️ Repository Structure

```text
notebooks/                  Course notebooks
docs/                       Dataset and lecture summaries
requirements.txt            Python dependencies
SETUP.md                    Local setup guide
```

## Validation

The CI workflow installs `requirements.txt`, compiles Python files, and checks
that every notebook is valid JSON. Notebook execution is intentionally not part
of CI because some lessons download datasets at runtime.

## License

Course text, notebooks, and educational material are licensed under
[Creative Commons Attribution 4.0 International](LICENSE).
