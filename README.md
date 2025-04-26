![Project Badge](images/ames_project_badge.png)

# 🏠 Ames Housing Price Prediction | Machine Learning Regression Project

## 📋 Overview

Predicting house prices using the Ames Housing dataset. Achieved **R² = 0.9344** using XGBoost.

## 🎯 Objectives
- Build an accurate regression model
- Apply feature engineering, data cleaning, and modeling techniques
- Evaluate using multiple models and select the best

## 🛠️ Technologies
- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- Statsmodels

## 🧠 Workflow
- Data Cleaning and Feature Engineering
- Feature Selection based on correlation and multicollinearity (VIF)
- Model Building: Linear Models → Tree-Based Models
- Final Evaluation using R², MAE, RMSE

## 📈 Results

| Model | R² Score | MAE | RMSE |
|:---|:---|:---|:---|
| Linear Regression | 0.8929 | \$16,445.98 | \$29,298.67 |
| Lasso | 0.8934 | \$16,755.46 | \$29,232.50 |
| Ridge | 0.8939 | \$16,600.70 | \$29,169.04 |
| Random Forest | 0.9136 | \$15,939.47 | \$26,325.13 |
| **XGBoost** | **0.9344** | **\$14,943.08** | **\$22,929.79** |

## 🔮 Future Work
- Hyperparameter tuning
- Model deployment (e.g., via Streamlit)
- Comparison with LightGBM or CatBoost
