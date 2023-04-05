# House price prediction using-Python

Chennai House Price Prediction is a popular dataset on Kaggle that contains information on various attributes of houses located in Chennai, India, such as the total square footage, number of bedrooms, location, and age of the house, among others. The goal of this dataset is to predict the selling price of a house based on its characteristics.

**Approach**

1) Importing libraries

2) Reading the concerned dataset

3) Data Understanding

4) Data cleaning

5) Data visualization

6) Splitting the Data and feature scaling

7) Building a various regression models like ("lm","rf","svmRadial","xgbTree","xgbLinear")

8) Ensembling the Models

9) Making Predictions Using the Models

10) Model Evaluation using RMSE

**Conclusion**

out of all RMSE values, XGBoost method gives the less error and High R squared value.

|Method | RMSE Values | R2 Values | 
| ----------- | ----------- | ----------- |
| Ensemble | 0.32 | 0.74 |
| SVM | 0.23 | 0.86 |
| RF  | 0.22 | 0.87 |
| XGBT | 0.19 | 0.91 |
| KNN | 0.26 | 0.82 |
