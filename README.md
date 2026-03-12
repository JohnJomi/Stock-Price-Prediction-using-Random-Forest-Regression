# Stock Price Prediction using Random Forest Regression

This project builds a machine learning model to predict stock closing prices using historical stock market data from the Yahoo Finance dataset. The model uses Random Forest Regression to learn patterns between stock features such as Open, High, Low, and Volume to estimate the closing price.

## Project Overview

Stock price prediction is a regression problem where the goal is to estimate a continuous value (closing price) using historical market data.

Features used in the model:
- Open Price
- High Price
- Low Price
- Volume

Target variable:
- Closing Price

## Dataset

The dataset is obtained from Yahoo Finance and contains historical stock market information.

Columns in the dataset include:
- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Machine Learning Model

The project uses Random Forest Regression, an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

## Workflow

1. Load dataset from Excel file
2. Perform data preprocessing
3. Select relevant features
4. Split dataset into training and testing sets
5. Train Random Forest Regression model
6. Predict stock closing prices
7. Evaluate model performance using MAE, MSE, and R² score
8. Visualize actual vs predicted values

## Model Evaluation Metrics

The model is evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/stock-price-prediction.git

2. Open the notebook in Google Colab or Jupyter Notebook

3. Upload the dataset file `yahoo_data.xlsx`

4. Run all cells to train and evaluate the model

## Project Structure

stock-price-prediction/
│
├── stock-price-prediction.ipynb
├── yahoo_data.xlsx
└── README.md

## Future Improvements

- Add technical indicators such as Moving Average and RSI
- Use deep learning models like LSTM
- Perform hyperparameter tuning
- Include additional market indicators

## Disclaimer

This project is for educational purposes only and should not be used for real financial or investment decisions.
