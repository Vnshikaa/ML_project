House Price Prediction using Linear Regression

📌 Project Overview:

This project predicts house prices based on the living area of a house (sqft_living) using a Linear Regression model.

The goal is to understand the relationship between the size of a house and its market price and build a simple machine learning model to make predictions.

🎯 Objective:

1.Analyze the relationship between house size (square feet) and price

2.Build a Linear Regression model to predict house prices

3.Visualize the data and regression line

4.Evaluate the model performance using Mean Squared Error (MSE)

📊 Dataset:

The dataset contains housing information including:

1.sqft_living – Area of the house in square feet

2.price – Price of the house

These features are used to train and test the machine learning model.

🛠 Technologies Used:

1.Python
2.NumPy
3.Pandas
4.Matplotlib
5.Scikit-learn
7.Google Colab

⚙️ Model Used:

Linear Regression-

Linear regression models the relationship between the independent variable (sqft_living) and the dependent variable (price) by fitting a straight line to the data.

📈 Data Visualization:

A scatter plot was created to visualize the relationship between house size and price.

The red line represents the Linear Regression model prediction line.

This helps to understand how house prices generally increase with larger living areas.

📉 Model Evaluation:

The model performance was evaluated using Mean Squared Error (MSE).

Lower MSE values indicate better prediction accuracy.

Example result:
MSE ≈ 9.9e10

📌 Project Workflow:

1.Import libraries

2.Load dataset

3.Select features (sqft_living)

4.Split data into training and testing sets

5.Train Linear Regression model

6.Predict house prices

7.Visualize regression line

8.Evaluate model using MSE

📷 Output:

The model generates a scatter plot showing:

1.Actual house prices

2.Predicted regression line

This demonstrates how house prices change with increasing living area.

🚀 Future Improvements:

1.Use multiple features such as bedrooms, bathrooms, and location

2.Try advanced models like Random Forest or Gradient Boosting 

3.Improve prediction accuracy with feature engineering
