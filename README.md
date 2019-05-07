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
