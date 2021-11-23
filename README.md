# Car-price-prediction-ML
A machine learning model to predict car prices. Dataset: https://www.kaggle.com/hellbuoy/car-price-prediction

### Problem Statement

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car
How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.

### Goal

We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

*P.S.: The dataset provided is for learning purpose. Please don’t draw any inference with real world scenario.*

## My Approach
* Clearly, this is a **Linear regression** problem.
* First, I imported data from csv, then did some data exploration using **pandas, seaborn and matplotlib**.
* Then, did some pre processing like One hot Encoding.
* Then split data into train and test using `sklearn.model_selection.train_test_split`.
* Then trained a Linear regression model and achieved 91.5 % accuracy against test data set.
* The accuracy is further improved using **L2 or Ridgre regression**. The final accuracy is 94.41 %.
* I finally exported the model to a joblib file.
