# S&P 500 Stock Price Prediction in Google Colab

This Google Colab notebook demonstrates a machine learning approach to predict S&P 500 stock price movements using historical data exported from yahoo fianace

## Features

- Data retrieval using yfinance
- Data preprocessing and feature engineering
- Implementation of a Random Forest Classifier
- Backtesting strategy
- Performance evaluation using precision score

## Libraries Used

- yfinance
- pandas
- scikit-learn
- matplotlib

## Key Steps

1. Fetch S&P 500 historical data
2. Create target variable (price increase/decrease)
3. Engineer features including rolling averages and trends
4. Implement and train Random Forest Classifier
5. Backtest the model on different time periods
6. Evaluate model performance

## Results

The final model achieves a precision score of approximately 0.574, indicating moderate predictive power for S&P 500 price movements.

## Usage

Run the notebook cells sequentially in Google Colab or similar programs i.e jupyter notebook/lab to reproduce the analysis and results.

## Next Steps

1. Experiment with different machine learning models (e.g. LSTM)
2. Take into account other indexes that are not the S&P
3. monitor the news
