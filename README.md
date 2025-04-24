
# London House Price Prediction

This project builds a machine learning model to predict house prices in London using advanced data preprocessing, feature engineering, and linear regression.

## Project Overview

The notebook focuses on building a robust pipeline for predicting house prices in London using various property features. It performs extensive data cleaning, transformation, and evaluation to ensure the model’s effectiveness.

## Key Features

- Dataset: `train.csv` and `test.csv` 
- Preprocessing:
  - Handling missing values  
  - Outlier detection using IQR  
  - Feature encoding for categorical variables  
  - Log transformation of skewed target variable (`price`)
- Feature Engineering:
  - Ratios like `bed_bath_ratio`, `area_per_bedroom`  
  - Calculated features like `property_age`
- Modeling:
  - Linear Regression using `scikit-learn`
  - Robust feature scaling
- Evaluation:
  - Metrics: Mean Squared Error (MSE), R² Score
  - Visualization of predictions vs. actual values

## File Structure

```
london-house-price-prediction
├── README.md
├── london-house-price-prediction.ipynb
├── submission.csv
└── data/
    ├── train.csv
    └── test.csv
```

## Results

- Public Kaggle Score: **251019.423370**
- Rank: **95th out of 225 submissions**
- Validation MSE: £268612349327.51
- Validation R²: 0.6380
- Predicted prices closely matched real values (visualized using a scatter plot)

## Tech Stack

- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  


