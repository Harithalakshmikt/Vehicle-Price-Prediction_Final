# Vehicle Price Prediction

This project builds a machine learning model to predict vehicle prices based on various features such as mileage, year, brand, and condition. The model uses XGBoost regression to estimate the price of vehicles.

## Dataset
The dataset includes features relevant to vehicle specifications and historical prices. The data was preprocessed to handle missing values and encode categorical variables.

## Model
- Algorithm: XGBoost Regressor
- Performance metrics:
  - MAE (Mean Absolute Error): $4,779.33
  - RMSE (Root Mean Squared Error): $6,955.56
  - R² Score: 0.8416

These results indicate the model explains approximately 84% of the variance in vehicle prices and provides reasonably accurate price predictions.

## Usage
1. Clone the repository.
2. Install required packages listed in `requirements.txt`.
3. Run the Jupyter notebook or Python script to train and test the model.
4. Use the model to predict vehicle prices on new data.

## Future Work
- Improve feature engineering to enhance model accuracy.
- Experiment with other regression models.
- Use larger and more diverse datasets for better generalization.

## Author
Haritha lakshmi.K.T

