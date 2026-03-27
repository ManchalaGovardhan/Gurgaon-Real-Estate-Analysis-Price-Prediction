
# 🏡 Gurgaon Real Estate Analysis & Price Prediction

## 📌 Project Overview

This project focuses on analyzing and predicting real estate prices in Gurgaon using data collected through web scraping. It covers the complete data science workflow including data cleaning, feature engineering, exploratory data analysis, and machine learning model building, along with a Streamlit application for real-time predictions and analysis.

## 🔄 Project Workflow

```
Web Scraping
   ↓
Excel Cleaning
   ↓
Python Data Cleaning
   ↓
Feature Engineering
   ↓
EDA
   ↓
Outlier Handling
   ↓
Missing Value Imputation
   ↓
Feature Selection
   ↓
Analysis
   ↓
Prediction
   ↓
Streamlit App
```

---

## 📊 Dataset

The dataset consists of Gurgaon property data including:

* Flats and Apartments → `appartments.csv`, `flats - flats.csv`
* Independent Houses → `independent-house - independent-house.csv`
* Location coordinates → `latlong.csv`

### Processed Data Files:

* `flats_cleaned.csv`
* `house_cleaned.csv`
* `gurgaon_properties_merged.csv`
* `gurgaon_properties_cleaned_v1.csv`
* `gurgaon_properties_cleaned_v2.csv`
* `gurgaon_properties_missing_value_imputation.csv`
* `gurgaon_properties_outlier_treated.csv`
* `gurgaon_properties_post_feature_selection.csv`

---

## 🔍 Exploratory Data Analysis

Performed using:

* `eda-univariate-analysis.ipynb`
*  HTML report → `output_report.html`(pandas_profiling )-for bivariate analysis
* `eda-multivariate-analysis.ipynb`
* `data-visualization.ipynb`

---

## ⚙️ Data Preprocessing

* Flats preprocessing → `data-preprocessing-flats.ipynb`
* Houses preprocessing → `data-preprocessing-houses.ipynb`
* Merged data preprocessing → `data-preprocessing(merged gurgaov- data)-level-2.ipynb`
* Missing value handling → `missing-value-imputation.ipynb`
* Outlier treatment → `outlier-treatment.ipynb`
* Data merging → `merge-flats-and-house.ipynb`

---

## 🧠 Feature Engineering & Selection

* `feature-engineering.ipynb`
* `feature-selection.ipynb`

---

## 🤖 Model Building

* Baseline model → `baseline model.ipynb`
* Model selection → `model-selection.ipynb`

---

## 📈 Output

* Final processed dataset
* Prediction-ready data
* HTML report → `output_report.html`

---

## 🚀 Application

A Streamlit app is developed (in `app/` folder) to:

* Analyze property data
* Predict property prices based on user input

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Streamlit

---
