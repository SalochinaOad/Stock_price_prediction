# Stock_price_prediction S&P 500

This project uses historical S&P 500 index data to predict whether the market will go up the next day. It applies a Random Forest classifier on features like Open, High, Low, Close, and Volume.

### Project Structure
Data Source: yfinance pulls historical S&P 500 (^GSPC) data

Target: Whether the market goes up the next day (1) or not (0)

Model: RandomForestClassifier with minimal tuning

Evaluation: Precision score on the last 100 days as test data


### Output
Line plot of historical S&P 500 Close prices

Prediction results for the last 100 days

Precision score for model performance
