## StockProphet

### Overview

This repository contains web application for predicting the future stock prices of selected companies. The app  uses stock price data retrieved from Yahoo Finance, performs time series forecasting using the Prophet library, and visualizes the forecasted prices and components.

### Features

- Select a company (AAPL, GOOG, MSFT) and specify the number of years for prediction.
- View the raw dataset, forecasted dataset, and forecast plot.
- Visualize forecast components such as trend, seasonality, and holidays.

### Installation 

Clone the repository:
   
   ```
   git clone https://github.com/sreedeepEK/StockProphet
   ```
Install the required dependencies:
   
   ```
   pip install -r requirements.tx
   ```


### Usage

Run the following command to launch the Streamlit app:

   ```
   streamlit run app.py
   ```
### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
