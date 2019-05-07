# MachineLearningStocks
Using python to make stock predictions

MachineLearningStocks is designed to be an intuitive and highly extensible template project applying machine learning to making stock predictions. My hope is that this project will help you understand the overall workflow of using machine learning to predict stock movements and also appreciate some of its subtleties. And of course, after following this guide and playing around with the project, you should definitely make your own improvements.


As a disclaimer, this is a purely educational project. Be aware that backtested performance may often be deceptive – trade at your own risk!

# Overview
The overall workflow to use machine learning to make stocks prediction is as follows:

Acquire historical fundamental data – these are the features or predictors
Acquire historical stock price data – this will make up the dependent variable, or label (what we are trying to predict).
Preprocess data
Use a machine learning model to learn from the data
Backtest the performance of the machine learning model
Acquire current fundamental data
Generate predictions from current fundamental data
This is a very generalised overview, but in principle this is all you need to build a fundamentals-based ML stock predictor.


# Quickstart
If you want to throw away the instruction manual and play immediately, clone this project, then download and unzip the data file into the same directory. Then, open an instance of terminal and cd to the project's file path, e.g

     cd Users/User/Desktop/MachineLearningStocks
Then, run the following in terminal:

     pip install -r requirements.txt
     python download_historical_prices.py
     python parsing_keystats.py
    python backtesting.py
    python current_data.py
    pytest -v
    python stock_prediction.py
