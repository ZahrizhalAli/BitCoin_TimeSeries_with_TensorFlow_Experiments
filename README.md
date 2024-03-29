# BitCoin Prediction - Time Series

Made by : Zahrizhal Ali

This project aims to predict future prices of Bitcoin using time series analysis. The Bitcoin Prediction Time Series project utilizes historical Bitcoin price data and employs various machine learning techniques to forecast the future price movements of Bitcoin. This documentation provides a comprehensive guide to the project, including its features, installation instructions, usage, and data sources. 

Tech Used: Python, Pandas, Matplotlib, TensorFlow, Scikit-Learn, Data Analysis and Visualization.
The Bitcoin Prediction Time Series project leverages the following libraries and resources:

* [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
* [Scikit-learn](https://scikit-learn.org/stable/) for machine learning algorithms.
* [Matplotlib](https://matplotlib.org/) for data visualization.
* [NumPy](https://numpy.org/) for numerical operations.
* [TensorFlow](https://www.tensorflow.org/) for deep learning models/algorithms implementation.

## Features
* Working with time series data (historical price of Bitcoin)
* Formatting data for a time series specific problem
* Implements naive bayes deep learning algorithms for time series forecasting
* Provides evaluation metrics to assess the accuracy of predictions
* Includes data visualization to aid in understanding and brief analysis.
* Technique for specific future prediction.

## How to use this notebook

A better option is to write all the code yourself using Google Colab to get the most out of hands-on experience or directly import this .ipynb format to google colab or your local environment.


## Dataset
The Bitcoin Prediction Time Series project requires historical Bitcoin price data. You can obtain such data from various sources, such as cryptocurrency exchanges or online financial platforms. Ensure the data is in CSV format and contains the necessary information (e.g., date and closing price).
This dataset is collected from 01 October 2013 to 18 of May 2021 using Coindesk dataset sources. You can find alternative link to the dataset used [here](https://raw.githubusercontent.com/mrdbourke/tensorflow-deep-learning/main/extras/BTC_USD_2013-10-01_2021-05-18-CoinDesk.csv).

## Keypoint Experiments
* Naive Forecast model (baseline)
* Dense 
* Conv1D
* LSTM (Long Sort Term Memory)
* Multivariate LSTM
* N-BEATs Algorithm (from N-BEATs Paper documentation)
* Ensemble Model

## Keyfindings

![image](https://github.com/ZahrizhalAli/BitCoin_TimeSeries_with_TensorFlow_Experiments/assets/58893316/722b5941-fee5-4f51-8d66-0e2af614bc94)

From plotted functoin that Returns array of datetime values ranging from start_date to start_date + into_future

The Bitcoin Prediction Time Series project provides a comprehensive framework for predicting Bitcoin prices based on historical data. By utilizing deep learning algorithms and time series analysis, this project empowers users to explore and forecast future price movements. With its intuitive features and customizable nature, it offers a valuable tool for analysis in this field.


