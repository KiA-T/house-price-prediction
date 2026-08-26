# House Price Prediction using CatBoost

A machine learning project for predicting house prices using Python and CatBoost.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Matplotlib
- Seaborn

## Dataset

The dataset contains information about houses such as:

- Area
- Bedrooms
- Bathrooms
- Floors
- Age
- Parking
- City
- HasGarden
- HasPool
- Furnished
- DistanceToCenter
- CrimeIndex
- SchoolScore

## Model

The project uses **CatBoostRegressor** to predict house prices.

The data is split into training and testing sets, and categorical data is converted using One-Hot Encoding.

## Evaluation

The model achieved:

- **MAE:** 47,282.97
- **R² Score:** 0.849

## Project Structure

```text
house-price-prediction/
│
├── house_price_prediction.ipynb
├── house_prices.csv
└── README.md
