# Heart Failure Disease Prediction

Machine learning project that predicts the likelihood of heart disease from patient clinical attributes (age, chest pain type, resting BP, cholesterol, ECG results, and more).

## What it does
1. Loads the heart failure dataset (`heart.csv`)
2. One hot encodes categorical features
3. Trains and compares Decision Tree, Random Forest, and XGBoost models
4. Evaluates models with accuracy and tunes hyperparameters

## Dataset
Not included in this folder. Download the Heart Failure Prediction dataset (Kaggle, fedesoriano) and place `heart.csv` next to the notebook.

## Tech stack
Python, pandas, NumPy, scikit-learn, XGBoost, Matplotlib

## Run it
```bash
pip install pandas numpy scikit-learn xgboost matplotlib
jupyter notebook HeartDisease_Project.ipynb
```
