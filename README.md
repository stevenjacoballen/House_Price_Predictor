# Project Intro
This Project utilizes Regression models to predict housing prices in the Seattle area based on sales data from 2014-2015. The model that performs the best will be deployed with Flask on AWS EC2.

In this case, the Linear Regression model ultimately performs best, and consequently, the four assumptions of Linear Regression are tested. After finding that two of the assumptions are violated, the label data price is log-transformed, the Linear Regression model is retrained, the assumptions are re-tested, and a final analysis is conducted.

The web app is simply designed and outputs a predicted price based on the user's inputs (square footage, number of bedrooms, etc.).

## Project Outline
1. EDA & Data Cleaning
2. Machine Learning
3. Preliminary Results
4. Log-Transform Price & Retrain Best Model
5. Conclusion
6. Export Model for Deploymen

## Links
[Dataset](https://github.com/stevenjacoballen/House_Price_Predictor/blob/main/housing_data.csv)  
[Web App](http://ec2-50-17-105-101.compute-1.amazonaws.com/)
