
# 🏡 Gurgaon Real Estate Analysis & Price Prediction

📖 Overview

This project focuses on analyzing Gurgaon’s real estate market by collecting property data through web scraping and applying data science techniques. It covers the complete workflow, including data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning model development to predict property prices. The project also aims to help customers better understand and analyze the Gurgaon real estate market. Additionally, a Streamlit application has been developed to provide real-time price predictions and interactive insights.

❗ Problem Statement
Real estate price estimation is complex due to multiple influencing factors such as location, property size, amenities, and property type. This project aims to develop a reliable prediction system to accurately estimate property prices in Gurgaon. Additionally, it provides interactive visualizations and analytical insights to help users better understand market trends and make informed real estate decisions.

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
🏙️ Gurgaon Real Estate Analysis & Price Prediction

Gurgaon Real Estate Analysis & Price Prediction

mpacts property prices
Property type (flat vs house) affects pricing trends
Area, number of rooms, and amenities strongly influence price
Outlier handling improves model performance
📈 Dashboard / Model / Output
Machine learning models for price prediction
Performance comparison of multiple models
Interactive Streamlit App for:
Property analysis
Real-time price prediction
▶️ How to Run this Project
Clone the repository:
git clone <your-repo-link>
cd <project-folder>
Install dependencies:
pip install -r requirements.txt
Run the Streamlit app:
streamlit run app/app.py

📊 Results & Conclusion
Built a robust end-to-end pipeline for real estate price prediction
Achieved reliable prediction accuracy using machine learning models and created visualizations to understand key factors influencing property prices
Developed a Streamlit application that provides an intuitive and user-friendly interface for real-time predictions and analysis

🔮 Future Work
Integrate more real-time data sources
Use advanced models like XGBoost or Deep Learning
Deploy the application on cloud platforms (AWS/GCP/Azure)
Add more features like rental price prediction
👤 Author & Contact

Manchala Govardhan
ph:7671939221
mail:manchalagovardhan91@gmail.com
