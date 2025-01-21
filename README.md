## Car Price Prediction using Linear Regression and Lasso Regression

This project focuses on predicting the selling price of used cars based on various features such as fuel type, seller type, transmission, and other car attributes. The goal is to use machine learning techniques to build predictive models, compare their performance, and visualize the results.

### Project Overview

In this project, we work with a dataset of used cars containing several features that influence their selling price. The process involves cleaning the dataset, encoding categorical variables, and applying two machine learning algorithms — Linear Regression and Lasso Regression — to predict the car's selling price.

### Steps Involved:

1. **Data Exploration**:
   - The dataset is loaded and basic exploratory data analysis (EDA) is performed.
   - We check for missing values and get a summary of the dataset.
   - We inspect the distribution of categorical variables like `Fuel_Type`, `Seller_Type`, and `Transmission`.

2. **Data Preprocessing**:
   - Categorical variables (`Fuel_Type`, `Seller_Type`, `Transmission`) are encoded into numerical values to make them compatible with machine learning models.

3. **Feature Selection**:
   - The independent variables (`X`) are selected by dropping unnecessary columns like `Car_Name` and the target variable (`Selling_Price`) is separated.

4. **Splitting the Data**:
   - The dataset is split into training and testing sets (90% for training and 10% for testing).

5. **Modeling**:
   - **Linear Regression**: A linear regression model is trained on the training data, and its performance is evaluated using R-squared on both the training and test datasets.
   - **Lasso Regression**: Lasso regression is applied as a regularized version of linear regression to prevent overfitting. It is then evaluated similarly to linear regression.

6. **Performance Evaluation**:
   - The performance of both models is evaluated using R-squared (R²), which measures how well the model's predictions match the actual values.
   - Visualizations (scatter plots) are used to compare the actual vs predicted selling prices.

