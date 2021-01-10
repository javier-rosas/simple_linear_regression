# simple_linear_regression

Goal: 

  - Comparison of Multivariate Linear Regression Models 
    - **Data Discover:** Plot out all correlations among the features. You may notice some features are more correlated with your predicted value than other. This       information will help you confirm that weights of your regression model later on.

     - **Data Cleaning:** If your dataset has some missing values, make sure you are able to fill those values with the Imputer class. If your dataset has                categorical features, make sure you conver those features into numerical using OneHotEncoder class. 

     - **Feature Scaling** More importantly, your task is to write some codes to normalize the value of each features as follow:

      Subtract the mean value of each feature from the dataset
      Scale (divide) the feature values by their respective standard deviation
