# House Price Prediction

Predict the prices of residential houses using machine learning based on various features like size, number of rooms, location, etc.

# Introduction

Real estate pricing is influenced by numerous factors like area, number of bedrooms, location, etc. Accurately predicting house prices helps buyers, sellers, and agents make informed decisions.

In this project, we use supervised machine learning to build a **regression model** that predicts the price of a house based on its features. The model is trained on historical housing data and is capable of making reasonably accurate predictions for unseen data.

# Problem Statement

Develop a machine learning pipeline that can:

- Ingest and clean real estate data.
- Perform exploratory data analysis (EDA) to understand key price-driving features.
- Train and evaluate a regression model (like Linear Regression).
- Predict house prices for new input data.
- (Optional) Save and deploy the trained model.

# Dataset

We use the [Kaggle House Prices Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

# Features (examples):
- `LotArea`: Lot size in square feet
- `OverallQual`: Overall material and finish quality
- `YearBuilt`: Year the house was built
- `TotalBsmtSF`: Total basement area
- `GrLivArea`: Above grade (ground) living area
- `GarageCars`: Garage capacity
- `SalePrice`: Target variable (house price)
  
# Algorithms Used

- **Linear Regression**
- (Optional extensions): Ridge, Lasso, XGBoost

# Tech Stack
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Seaborn, Matplotlib (for EDA)
- Jupyter Notebook

# How to run 
1. Clone the Repository
  cd house-price-prediction
2. Install requirement 
  pip install -r requirements.txt
3. Run python script
  python main.py
