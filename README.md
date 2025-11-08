# 📄 Customer Churn Prediction

<div align="center">

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Python Version](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

**ML Pipeline to Predict Customer Churn with Feature Engineering & Ensemble Methods**

</div>

---

## 🎯 Overview

**Problem:** Customers are leaving services without clear warning - losing revenue and market share.

**Solution:** Build a predictive ML model to identify at-risk customers, enabling proactive retention strategies.

**Impact:** Improve customer retention rate and reduce churn through data-driven insights.

---

## ✨ Key Features

- ✅ **Data Preprocessing** - Handle missing values, outliers, and categorical encoding
- ✅ **EDA** - Comprehensive exploratory analysis with visualizations
- ✅ **Feature Engineering** - Create meaningful features from raw data
- ✅ **Ensemble Models** - Logistic Regression, Random Forest, XGBoost
- ✅ **Model Evaluation** - Accuracy, Precision, Recall, ROC-AUC metrics
- ✅ **Business Insights** - Identify key churn drivers

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | Python 3.8+ |
| **Data Processing** | Pandas, NumPy |
| **ML Frameworks** | Scikit-learn, XGBoost |
| **Visualization** | Matplotlib, Seaborn |
| **Notebooks** | Jupyter |

---

## 📊 Dataset

**Source:** [Telco Customer Churn - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

**Features:** 7043 records × 21 features
- **Target:** Churn (Yes/No)
- **Features:** Demographics, services, charges, tenure, etc.

---

## 🔍 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| **Logistic Regression** | 80.5% | 65.2% | 52.1% | 57.8% |
| **Random Forest** | 85.3% | 73.8% | 61.4% | 67.2% |
| **XGBoost** | **86.2%** | **75.1%** | **63.7%** | **68.9%** |

**Best Model:** XGBoost with 86.2% accuracy

---

## 📄 Key Insights

- **Top Churn Drivers:**
  1. Tenure (New customers churn more)
  2. Monthly Charges (Higher charges = higher churn)
  3. Internet Service Type (Fiber optic has highest churn)

- **Retention Strategies:**
  - Focus on customers in their first 6 months
  - Offer loyalty programs for high-charge customers
  - Improve Fiber optic service quality

---

## 📆 Project Structure

```
.
├── data/
│   ├── raw/                    # Original dataset
│   └── processed/             # Cleaned data
├── notebooks/
│   ├── 01_eda.ipynb           # Exploratory analysis
│   ├── 02_preprocessing.ipynb # Data cleaning
│   ├── 03_modeling.ipynb      # Model training
└── results/
    ├── plots/                 # Visualizations
    └── models/                # Trained models
```

---

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/JoelJoyston0705/customer-churn-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run analysis
jupyter notebook notebooks/01_eda.ipynb
```

---

## 💫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/joeljoyston)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/JoelJoyston0705)

---

**⭐ If you found this helpful, please star the repository!**
