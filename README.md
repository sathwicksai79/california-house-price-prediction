# California Housing Price Prediction

Predicting median house values using 1990 California census data.

## Models Used
- Linear Regression (baseline)
- Random Forest Regressor

## Results
| Model | R² | MAE | RMSE |
|---|---|---|---|
| Linear Regression | paste your number | paste your number | paste your number |
| Random Forest | paste your number | paste your number | paste your number |

## Libraries
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Dataset
California Housing dataset (1990 US Census)
Each row = one census block group in California
Target: Median house value

## What I Learned
- Random Forest significantly outperforms Linear Regression on this dataset
- Median income is the strongest predictor of house value
- Linear Regression can predict negative prices, which Random Forest avoids