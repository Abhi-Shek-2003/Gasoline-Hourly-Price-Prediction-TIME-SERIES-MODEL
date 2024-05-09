# Gasoline Hourly Prices Prediction

This repository contains code and resources for building a time series model to predict hourly gasoline prices. The model is trained on historical gasoline price data and aims to forecast future prices accurately.

## Dataset

The dataset used for training the model consists of hourly gasoline prices over a certain period. It includes features such as date, time, location, and possibly additional factors that influence gasoline prices, such as crude oil prices, taxes, etc.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow (optional, for deep learning models)
- Jupyter Notebook (optional, for running and modifying notebooks)

### Usage
Data Preprocessing: Preprocess the dataset by cleaning, normalizing, and splitting it into training and testing sets.
Model Training: Train different time series models such as ARIMA, SARIMA, Prophet, LSTM, etc., using the training dataset.
Evaluation: Evaluate the trained models using appropriate evaluation metrics such as RMSE, MAE, etc., on the test dataset.
Prediction: Use the best-performing model to make predictions on unseen data (future gasoline prices).

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.
