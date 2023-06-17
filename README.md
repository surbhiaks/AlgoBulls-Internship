# AlgoBulls-Internship
To run the code for the simple algorithmic trading strategy, follow the steps below:

1.Make sure you have the required libraries installed. If not, you can install them using the following command:
python

2.Open a Jupyter Notebook or any Python environment of your choice.

3.Copy and paste the entire code into a code cell.

4.Replace the value of the api_key variable with your own Alpha Vantage API key. You can get a free API key by signing up on the Alpha Vantage website.

5.Run each code cell sequentially.

The code will fetch intraday data for the specified stock symbols (GOOGL, NVDA, and AAPL), compute the moving average indicator, generate trading signals (BUY, SELL, NO_SIGNAL), and plot candlestick charts with the indicator overlaid. The trading strategy is based on the crossing of the moving average indicator with the closing price. The signals DataFrame will contain the timestamps and corresponding trading signals (BUY or SELL). Only the rows with BUY or SELL signals will be printed.
Please note that the code uses a 1-minute interval for intraday data and a time period of 5 for the moving average indicator. You can modify these parameters according to your requirements.

Additionally, ensure that you have a stable internet connection to fetch the data from Alpha Vantage successfully.Remember to comply with Alpha Vantage's terms of service and API usage guidelines when using their data for trading strategies.
