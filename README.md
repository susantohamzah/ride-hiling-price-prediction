# **Forecasting Ride-Hailing Prices with Linear Regression**

## **Objective**
The objective of this project is to utilize linear regression to predict ride-hailing prices accurately. By analyzing historical data such as distance, time, and demand, we aim to develop a model that can provide reliable fare estimations, benefiting both riders and drivers.

## **Problem Solved**
High variability in ride-hailing prices can lead to uncertainty and dissatisfaction among customers. By building a robust linear regression model, we aim to mitigate this issue by providing accurate fare predictions, improving customer satisfaction and driver earnings.

## **File Explanation**
- `P1G4_agus_susanto.ipynb`: Notebook for building the model, including data cleaning, data validation, and exploratory data analysis (EDA).
- `README.md`: Project overview and conclusions.

## **Tech Stack**
- **Programming Languages:** Python
- **Libraries/Frameworks:** Pandas, Scikit-learn, Matplotlib, Seaborn
- **Statistical Analysis:** Linear Regression

## **Dataset**
The dataset used in this project is sourced from [Uber and Lyft Dataset - Boston, MA](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma).

## **Conclusion**
The model built yields good results with an R2 score of 0.96 on both train and test datasets, indicating a successful prediction accuracy of 96% in estimating prices.
- **Intercept:** 2.1586, representing the base price for fare estimation when all independent variables are 0.
- Multivariate Normality test reveals potential issues such as missing important variables or some variables having non-linear relationships with the target.
- The dataset exhibits low linearity with the target variable, suggesting the need to explore alternative regression models.
- Further comparison tests can be conducted using Lasso Regression or Ridge Regression to address the shortcomings of the current model.
