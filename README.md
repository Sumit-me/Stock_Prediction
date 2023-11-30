
# Stock Prediction Web Application using Dash and Machine Learning
This project aims to provide a simple yet effective tool for stock market investors to visualize company stock data and make predictions based on machine learning models. The web application is built using the Dash framework, a Python library for building web applications with interactive user interfaces.

## Usage

To use the application, simply run the `app.py` file in your Python environment and open a web browser to the specified address. The user will be presented with a single page interface, where they can enter a company stock code and a date range for which they would like to see the stock data plotted. 

Once the user enters the stock code and date range, the application will fetch the relevant stock data using the yfinance library and plot the stock price data. Additionally, the user can select an option to view predicted stock prices based on a machine learning algorithm trained on the historical data.

## Dependencies

The following dependencies are required to run the application:

- Dash
- yfinance
- pandas
- scikit-learn
- plotly

The dependencies can be installed by running the following command in your Python environment:

```
pip install -r requirements.txt
```
```
python app.py
```

## Conclusion

This project provides a simple yet powerful tool for investors to visualize and analyze stock data of a specific company using machine learning models. It is a great project for beginners to learn about web application development, data visualization, and machine learning in Python.
