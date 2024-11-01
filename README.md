# Stock Market Prediction

This project involves predicting stock prices using two different methodologies: ARIMA (AutoRegressive Integrated Moving Average) and Stacked LSTM (Long Short-Term Memory). The project focuses on historical price data for TATA Global Beverages and Reliance Industries.

## Project Structure

The repository contains the following files:

- **ARIMA Model (RELIANCE Ind).ipynb**: Jupyter Notebook implementing the ARIMA model for predicting Reliance Industries stock prices.
- **ARIMA Model (TATA Ind).ipynb**: Jupyter Notebook implementing the ARIMA model for predicting TATA Global Beverages stock prices.
- **STOCK MARKET PREDICTION - STACKED LSTM(RELIANCE).ipynb**: Jupyter Notebook implementing the Stacked LSTM model for predicting Reliance Industries stock prices.
- **STOCK MARKET PREDICTION - STACKED LSTM(TATA).ipynb**: Jupyter Notebook implementing the Stacked LSTM model for predicting TATA Global Beverages stock prices.
- **NSE-RELIANCE.csv**: CSV file containing historical stock data for Reliance Industries.
- **NSE-TATAGLOBAL.csv**: CSV file containing historical stock data for TATA Global Beverages.
- **README.md**: This README file, providing an overview of the project.

## Methodologies

### ARIMA Model

The ARIMA model is used for time series forecasting. The implementation includes:

1. **Data Preprocessing**: Loading and preparing the historical stock price data.
2. **Stationarity Check**: Using the Augmented Dickey-Fuller test to check for stationarity in the price series.
3. **Model Fitting**: Fitting an ARIMA model to the training data and generating predictions.
4. **Residual Analysis**: Analyzing residual errors for model validation.
5. **Forecasting**: Forecasting future stock prices and visualizing the results.

### Stacked LSTM Model

The Stacked LSTM model is used for sequence prediction. The implementation includes:

1. **Data Preparation**: Processing the historical stock price data for training the LSTM model.
2. **Model Architecture**: Creating a stacked LSTM architecture to capture temporal dependencies.
3. **Training**: Training the LSTM model on the historical data.
4. **Evaluation**: Evaluating the model's performance on test data and visualizing the predictions.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `tensorflow`
- `statsmodels`
- `matplotlib`
- `seaborn`
- `pmdarima`

You can install the required libraries using pip:

```bash
pip install pandas numpy tensorflow statsmodels matplotlib seaborn pmdarima

Here's a README.md file that summarizes your stock market prediction project using ARIMA and LSTM models for TATA and Reliance stocks:
````
# Stock Market Prediction

This project involves predicting stock prices using two different methodologies: ARIMA (AutoRegressive Integrated Moving Average) and Stacked LSTM (Long Short-Term Memory). The project focuses on historical price data for TATA Global Beverages and Reliance Industries.

## Project Structure

The repository contains the following files:

- **ARIMA Model (RELIANCE Ind).ipynb**: Jupyter Notebook implementing the ARIMA model for predicting Reliance Industries stock prices.
- **ARIMA Model (TATA Ind).ipynb**: Jupyter Notebook implementing the ARIMA model for predicting TATA Global Beverages stock prices.
- **STOCK MARKET PREDICTION - STACKED LSTM(RELIANCE).ipynb**: Jupyter Notebook implementing the Stacked LSTM model for predicting Reliance Industries stock prices.
- **STOCK MARKET PREDICTION - STACKED LSTM(TATA).ipynb**: Jupyter Notebook implementing the Stacked LSTM model for predicting TATA Global Beverages stock prices.
- **NSE-RELIANCE.csv**: CSV file containing historical stock data for Reliance Industries.
- **NSE-TATAGLOBAL.csv**: CSV file containing historical stock data for TATA Global Beverages.
- **README.md**: This README file, providing an overview of the project.

## Methodologies

### ARIMA Model

The ARIMA model is used for time series forecasting. The implementation includes:

1. **Data Preprocessing**: Loading and preparing the historical stock price data.
2. **Stationarity Check**: Using the Augmented Dickey-Fuller test to check for stationarity in the price series.
3. **Model Fitting**: Fitting an ARIMA model to the training data and generating predictions.
4. **Residual Analysis**: Analyzing residual errors for model validation.
5. **Forecasting**: Forecasting future stock prices and visualizing the results.

### Stacked LSTM Model

The Stacked LSTM model is used for sequence prediction. The implementation includes:

1. **Data Preparation**: Processing the historical stock price data for training the LSTM model.
2. **Model Architecture**: Creating a stacked LSTM architecture to capture temporal dependencies.
3. **Training**: Training the LSTM model on the historical data.
4. **Evaluation**: Evaluating the model's performance on test data and visualizing the predictions.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `tensorflow`
- `statsmodels`
- `matplotlib`
- `seaborn`
- `pmdarima`

You can install the required libraries using pip:

```
pip install pandas numpy tensorflow statsmodels matplotlib seaborn pmdarima
git clone https://github.com/Amanrawat17/STOCK-MARKET-PREDICTION.git
cd STOCK-MARKET-PREDICTION
````
Open the Jupyter Notebook of your choice:

For ARIMA predictions, open ARIMA Model (TATA Ind).ipynb or ARIMA Model (RELIANCE Ind).ipynb.
For LSTM predictions, open STOCK MARKET PREDICTION - STACKED LSTM(RELIANCE).ipynb or STOCK MARKET PREDICTION - STACKED LSTM(TATA).ipynb.
Run the cells in the notebook to see the results and visualizations.
