# scikit-Learn

**Linear regression** can be plotted using the following libraries in Python:
 numpy, scipy, stats model and sckit learn. 

**Scikit-learn** is a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction.

* Exploring Boston Housing Data Set from scikitlearn module :
`import sklearn`
`from sklearn.datasets import load_boston`
`boston = load_boston()`
The object boston is a dictionary
print the feature names of boston data set :
`print boston.feature_names`

### fit a linear regression model steps

1- import linear regression from sci-kit learn module :
`from sklearn.linear_model import LinearRegression`
2- Get the data from data frame and store them as X values
3 -store linear regression object in a variable :
`lrm = LinearRegression()`


Some of inside linear regression object functions :

lm.fit() -> fits a linear model
lm.predict() -> Predict Y using the linear model with estimated coefficients
lm.score() -> Returns the coefficient of determination (R^2).

**train-test split :**
You can create training and test data sets for part od data frame manually or randomly using Scikit learn function called train_test_split 

If your graph of the data is perfect, then your data should be randomly scattered around a linear line 
