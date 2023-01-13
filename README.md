# Machine Learning Trading Bot

![Decorative image.](Images/14-challenge-image.png)

In this new generation, speed give a competitive advantage. That is why in this challenge, I combined the algorithmic trading skills with the financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets. Using computer algorithms can be beneficial when it comes on  buy and sell faster than human traders

## Background

In this Challenge, I assume a role of a financial advisor at one of the top five financial advisory firms in the world. The firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. 

## Plan is to:

* Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.

* Adjust the input parameters to optimize the trading algorithm.

* Train a new machine learning model and compare its performance to that of a baseline model.

* create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.

## Guide

The steps for this Challenge are divided into the following sections:

* Establish a Baseline Performance

* Tune the Baseline Trading Algorithm

* Evaluate a New Machine Learning Classifier

* Create an Evaluation Report

### Establish a Baseline Performance

here, I will

1. Import the OHLCV dataset into a Pandas DataFrame.

2. Generate trading signals using short- and long-window SMA values.

3. Split the data into training and testing datasets.

4. Use the `SVC` classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data.

5. Review the classification report associated with the `SVC` model predictions.

6. Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”.

7. Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.

8. Write my conclusions about the performance of the baseline trading algorithm 

### Tune the Baseline Trading Algorithm

In this section, I will tune, or adjust, the model’s input features to find the parameters that result in the best trading outcomes (The best will be based on comparing the cumulative products of the strategy returns)

1. Tune the training algorithm by adjusting the size of the training dataset. I will slice the data into different periods.

2. Tune the trading algorithm by adjusting the SMA input features. Adjust one or both of the windows for the algorithm. 

3. Choose the set of parameters that best improved the trading algorithm returns.

### Evaluate a New Machine Learning Classifier

In this section, I will use the original parameters that I used previously. But, I will apply them to the performance of a different machine learning models. 

1. I will import a new classifier, such as `AdaBoost`, `DecisionTreeClassifier`, and `LogisticRegression`.

2. Using the original training data as the baseline model, I will fit another model with the new classifier.

3. Backtest the new model to evaluate its performance.
