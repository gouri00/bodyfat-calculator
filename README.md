# 🧠 Body Fat Calculator – ML + Flask Web App

A complete machine learning + Flask web application that predicts **body fat percentage** using physical body metrics. The project includes data preprocessing, feature selection, regression modeling, hyperparameter tuning, and deployment via a clean Flask-based frontend.

---

## 📦 Features

- 📊 EDA using visual plots (histograms, boxplots, distribution curves)
- 🚫 Outlier detection (none found)
- 🧠 Feature selection using:
  - ExtraTreesRegressor importance
  - Mutual Information Gain
  - Correlation + Variance Inflation Factor (VIF)
- ⚙️ ML Models:
  - Linear, Ridge, Lasso Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- 🛠️ Model optimization via **RandomizedSearchCV**
- 🌐 **Flask Web App** for user interaction and predictions

---

## 📁 Dataset

- **File**: `bodyfat.csv`
- **Target**: `BodyFat` (percentage)
- **Features**: Age, Weight, Height, Abdomen, Wrist, etc.

---

## 🧱 Tech Stack

- **Python 3.8+**
- **Pandas, NumPy** – Data manipulation
- **Seaborn, Matplotlib** – Visualization
- **Scikit-learn** – Machine Learning & Tuning
- **Statsmodels** – VIF calculation
- **Flask** – Web backend
- **HTML/CSS + Bootstrap** – Frontend for UI

---

## 🚀 Run the Project Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/bodyfat-calculator.git
cd bodyfat-calculator
