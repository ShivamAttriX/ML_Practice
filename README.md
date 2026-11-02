# 🧠 Practice ML

A hands-on learning repository for practicing core **Machine Learning** and **Data Science** concepts — from raw data to production-ready models.

---

## 📌 About

This project is a structured practice ground to build and reinforce ML fundamentals through real datasets and notebooks. Each topic is explored in its own dedicated folder with step-by-step Jupyter notebooks.

---

## 📁 Project Structure

```
Practice_ML/
│
├── Data_Cleaning/                  # Handling messy, real-world data
│   ├── Data_Cleaning.ipynb
│   └── Nike_Sales_Uncleaned.csv
│
├── Preprocessing/                  # (coming soon)
├── EDA/                            # (coming soon)
├── Regression/                     # (coming soon)
├── Classification/                 # (coming soon)
│
├── requirements.txt
└── README.md
```

---

## 🗺️ Topics Covered

| # | Topic | Status |
|---|-------|--------|
| 1 | **Data Cleaning** | ✅ In Progress |
| 2 | **Preprocessing** | 🔜 Planned |
| 3 | **Exploratory Data Analysis (EDA)** | 🔜 Planned |
| 4 | **Regression** | 🔜 Planned |
| 5 | **Classification** | 🔜 Planned |
| 6 | **Feature Engineering** | 🔜 Planned |
| 7 | **Model Evaluation & Tuning** | 🔜 Planned |

---

## 🧹 Data Cleaning
Practicing techniques to deal with dirty, real-world data:
- Handling missing values (imputation, dropping)
- Fixing incorrect data types
- Removing duplicates
- Detecting and treating outliers
- Standardizing inconsistent categories

> **Dataset:** Nike Sales (Uncleaned) — `Data_Cleaning/Nike_Sales_Uncleaned.csv`

---

## ⚙️ Preprocessing
Transforming raw data into a format suitable for ML models:
- Feature scaling (normalization, standardization)
- Encoding categorical variables (Label, One-Hot, Ordinal)
- Train/Test splitting
- Handling class imbalance (`imbalanced-learn`)

---

## 📊 Exploratory Data Analysis (EDA)
Understanding datasets before modeling:
- Univariate & bivariate analysis
- Correlation heatmaps
- Distribution plots
- Interactive visualizations with Plotly

---

## 📈 Regression
Predicting continuous target variables:
- Linear Regression
- Polynomial Regression
- Ridge / Lasso / ElasticNet
- XGBoost Regressor, LightGBM, CatBoost
- Evaluation: MSE, RMSE, MAE, R²

---

## 🏷️ Classification
Predicting categorical outcomes:
- Logistic Regression
- Decision Trees, Random Forests
- SVM, KNN, Naive Bayes
- Gradient Boosting (XGBoost, LightGBM, CatBoost)
- Evaluation: Accuracy, Precision, Recall, F1, ROC-AUC

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| `numpy` / `pandas` | Data manipulation |
| `matplotlib` / `seaborn` | Static visualizations |
| `plotly` | Interactive visualizations |
| `scikit-learn` | ML models & preprocessing |
| `xgboost` / `lightgbm` / `catboost` | Gradient boosting models |
| `statsmodels` | Statistical analysis |
| `imbalanced-learn` | Handling class imbalance |
| `joblib` | Model serialization |

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
https://github.com/ShivamAttriX/ML_Practice
cd ML_Practice

# 2. Create and activate virtual environment
python -m venv .venv
.venv\Scripts\activate        # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook
```

---

## 📝 Notes

- Each notebook is self-contained and heavily commented for learning purposes.
- Datasets are included in their respective topic folders.
- New topics and notebooks will be added progressively.

