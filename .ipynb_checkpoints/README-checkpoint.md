# Machine-Learning-Trading

## Overview
In this project, we step into the shoes of a financial advisor at a top financial advisory firm that uses advanced technology like machine learning algorithms and high-speed trading algorithms to maintain a competitive edge in the market. The aim of this project is to improve existing algorithmic trading systems by integrating them with machine learning algorithms, which have the potential to adapt quickly to new data.

The project is divided into four main steps:

Establish a Baseline Performance
Tune the Baseline Trading Algorithm
Evaluate a New Machine Learning Classifier
Create an Evaluation Report

## 1. Establish a Baseline Performance
The initial step involves running a provided starter code to establish a baseline performance. This includes importing the OHLCV (Open, High, Low, Close, Volume) dataset, generating trading signals using SMA (Simple Moving Average) values, splitting the data into training and testing sets, fitting an SVC (Support Vector Classification) model, creating a predictions DataFrame, and finally visualizing the actual returns vs. the strategy returns.

## 2. Tune the Baseline Trading Algorithm
Next, we tune the model’s input features to achieve better trading outcomes. This step involves adjusting the size of the training dataset and the SMA input features. Various combinations of parameters are tested to identify the set that yields the highest strategy returns.

## 3. Evaluate a New Machine Learning Classifier
In this step, we evaluate a new machine learning classifier (such as AdaBoost, DecisionTreeClassifier, or LogisticRegression) using the original parameters provided in the starter code. The new model is then backtested to evaluate its performance against the baseline model and the tuned trading algorithm.

## 4. Create an Evaluation Report
Finally, an evaluation report is created summarizing the findings of the project. This includes conclusions about the performance of the baseline trading algorithm, the effects of tuning the trading algorithm, and the evaluation of the new machine learning classifier.

## Conclusion
Through this project, we aim to understand the application and effectiveness of machine learning classifiers in improving algorithmic trading. The detailed analysis and findings from the project can provide valuable insights for financial advisors and firms looking to incorporate machine learning in their trading strategies.