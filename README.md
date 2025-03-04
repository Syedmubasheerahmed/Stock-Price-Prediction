# Stock-Price-Prediction
The Stock Trend Prediction project is a web-based application that utilizes deep learning techniques, specifically Long Short-Term Memory (LSTM) networks, to predict stock prices. It allows users to input a stock ticker, fetches historical stock data, and displays various stock trend charts, including candlestick charts, along with predictions. The project leverages the power of Keras for deep learning model training, Flask for creating the web application interface, Bootstrap for styling the front-end, and several other essential libraries.

Key Features:

Stock Ticker Input: Users can input a stock ticker symbol to fetch the corresponding historical stock data.

Historical Stock Data: The application uses the yfinance library to download historical stock data from January 2015 to the current date.

Descriptive Data: The application provides descriptive statistics of the historical stock data.

Exponential Moving Averages (EMA): It calculates and plots the Exponential Moving Averages for 20, 50, 100, and 200 days.

Data Splitting and Scaling: The historical stock data is split into training and testing datasets, and scaled using MinMaxScaler from the sklearn library.

LSTM Model: The application utilizes a Long Short-Term Memory (LSTM) network to predict stock prices based on historical data.

Candlestick Charts: The application generates and displays interactive candlestick charts using Plotly to visualize stock price movements.

Prediction vs Original Trend: It plots the predicted stock prices against the original prices for comparison.

Interactive Charts: The application displays interactive charts for various stock trends and predictions.

Downloadable Dataset: Users can download the historical stock dataset as a CSV file.

Technologies Used:

Python: The core programming language used for data processing and model prediction.

Keras: The deep learning library used to build and train the LSTM model.

Flask: The web framework used to create the web application interface.

yfinance: The library used to fetch historical stock data.

Pandas: For data manipulation and analysis.

Matplotlib & Plotly: For plotting the stock trend charts, including candlestick charts.

sklearn (Scikit-learn): For data preprocessing, specifically using MinMaxScaler.

Bootstrap: For styling the web application interface.

How It Works:

User Input: Users enter a stock ticker symbol in the input field and submit the form.

Data Fetching and Processing: The application fetches historical stock data, calculates EMAs, splits, and scales the data using MinMaxScaler.

LSTM Prediction: The LSTM model predicts the stock prices based on the processed data.

Visualization: The application generates and displays various charts, including candlestick charts, to visualize the stock trends and predictions.

Download Option: Users can download the historical stock data as a CSV file.
