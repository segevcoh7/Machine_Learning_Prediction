# Machine Learning Prediction - House Prices

## 📌 Project Overview
This project focuses on predicting house prices using **machine learning techniques** with the **Sberbank dataset**. The best-performing model was **XGBoost**, achieving an RMSLE of **0.330** after data cleaning, feature engineering, and hyperparameter tuning.

## 📂 Project Structure
- `notebooks/` - Contains Jupyter notebooks for data analysis and modeling.
- `reports/` - Includes project summary, documentation, and presentation files.
- `code/` - Stores the final code for the predictions.
- `submittion/` - Contains the final predictions for housing prices.
- `README.md` - Project introduction.

## 📊 Model Performance
| Method | RMSLE |
|--------|------|
| Baseline | 0.469 |
| Feature Engineering | 0.334 |
| KNN Imputation | 0.331 |
| Hyperparameter Tuning | 0.330 |

## ⚙️ Dependencies
To run the Jupyter notebook, install dependencies:
```bash
pip install -r requirements.txt
