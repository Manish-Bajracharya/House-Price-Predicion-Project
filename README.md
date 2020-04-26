# House Price Prediction Project
The aim of the project is to build a machine learning model to predict price of a house based on various features available which describe different aspects of a house.
 
## How does it help?
Predicting a house price is useful to determine whether it's been priced reasonably or to identify if buying that house will be a good investment or not.
 
## Objective
To minimise the error between predicted price and real price. We will evaluate the model performance using mean squared erro and root squared of the mean squared error.
 
## Process
Firstly, we will be pre-processing the data, which consists of 3 steps :

1. Data Analysis (DataAnalysis.ipynb) - We will be exploring data to identify :
     - Missing values
     - Numerical variables
     - Distribution of numerical variables
     - Outliers
     - Categorical variables
     - Cardinality of categorical variables
     - Relationship between features and target variable.
     
2. Feature Engineering (FeatureEngineering.ipynb) - We will engineer the variables to tackle:
     - Missing values
     - Temporal variables
     - Non-Gaussian distributed variables
     - Categorical variables - remove rare labels
     - Encode categorical variables
     - Feature scaling
     
3. Feature Selection (FeatureSelection.ipynb) - we will select features which are the most predictive ones to build our machine learning model using Lasso regression algorithm.

Then, we will build a model to predict SalePrice

4. Model Building (ModelBuilding.ipynb) - We will use Regularised Linear Regression - Lasso to predict our target variable. We will use MSE, RMSE and R2 for evaluation. We will also look at feature importance.

