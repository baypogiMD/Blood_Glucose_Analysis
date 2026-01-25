# Blood Glucose Missingness Analysis

## Overview
This project analyzes a clinical laboratory dataset that explicitly includes
patients **with and without blood glucose measurements**. Unlike traditional
datasets where missing values are treated as noise, this project treats
**missingness as an informative clinical signal**.

The objective is to:
- Understand patterns of glucose testing
- Quantify systematic missingness
- Evaluate modeling bias introduced by glucose availability
- Derive clinical and public health insights

---

## Dataset
**Source:** Kaggle – Dataset With/Without Blood Glucose Values  (https://www.kaggle.com/datasets/dwufoo/dataset-withwithout-blood-glucose-values)
**Records:** 5,905  
**Features:** 42 laboratory and demographic variables  

The dataset includes:
- Hematology indicators
- Metabolic and enzymatic markers
- Blood glucose–related biomarkers
- Structured missingness reflecting clinical workflows

---

## Key Research Questions
1. Is blood glucose missingness random or systematic?
2. How do patients with and without glucose tests differ clinically?
3. Does glucose availability bias predictive models?
4. Can missingness-aware features improve model robustness?

---

## Notebooks Overview

| Notebook | Description |
|-------|------------|
| 01 | Data loading, schema inspection, cleaning |
| 02 | Missingness patterns and cohort definition |
| 03 | Exploratory clinical and lab analysis |
| 04 | Feature engineering and encoding |
| 05 | Predictive modeling |
| 06 | Model evaluation and interpretability |
| 07 | Clinical and public health insights |

---

## Methods
- Descriptive statistics
- Missingness analysis (MCAR vs MAR)
- Statistical testing
- Machine learning (logistic regression, tree-based models)
- Model interpretability (feature importance, SHAP if applicable)

---
