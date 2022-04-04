# Car-Sales-Prediction
## Table Of Content
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
- [Installation](#installation)
- [To Do](#to-do)
## Overview
This simple regression project comprises an **Artificial Neural Network** to predict the estimate of the amount that the customer is willing to spend on a car. Here, we have made use of **(Gender, Age, Annual Salary, Credit Card Debt & Net-Worth)** to gauge the amount. 
## Motivation
What is the best way to acquire proficiency in a library? To practically implement a simple project utilizing that library, to learn its dependencies & respective functions for the further implementation of complex applications. My basic idea was to explore Tensorflow & Keras library which lead me to find the following Dataset for practical execution.

## Technical Aspect 
The dataset utilized for this project has the respective columns **(Customer Name, Customer e-mail, Country, Gender, Age, Annual Salary, Credit Card Debt, Net Worth, Car Purchase Amount)**. For the regression model, I have considered **(Gender, Age, Annual Salary, Credit Card Debt & Net Worth)**. For the output, **(Car Purchase Amount)** is considered.

The libraries utilized are **Seaborn, Pandas, TensorFlow, Keras & NumPy**. I have normalized the input columns using MinMaxScaler which helps the model to better generalize on the dataset as well as decreases the amount of computation time for the model by some amount and helps in the problem of vanishing & exploding gradient. The data is then segregated into training & testing, further a simple ANN architecture is utilized for prediction. The following represents the model loss for training & validation:


![](https://github.com/gauravshipurkar/Car-Sales-Prediction/blob/main/Images/Loss.png)


**Testing:**


![](https://github.com/gauravshipurkar/Car-Sales-Prediction/blob/main/Images/Result.png)

## Installation
The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/release/python-380/). To install the required packages and libraries, run this command in the project directory after cloning the repository:
```
pip install -r requirements.txt

```
## To Do
Further, we can do an analysis for this project utilizing diverse models and comparing the outputted results & thus select the best model.