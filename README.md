# Validation-methods

The obecjtive of this notebook is to compare different validation methods. For this, we will be using a dataset from the UCI repository. 
It is a crime rate data from different communities. There are 101 predictor variables such as household size, number of police officers, population, etc. The goal is to predict the total number of non-violate crimes per 100k population (response).

The python code and csv can be found in this repository

We will use Lasso regression for our prediction model. Since there are many variables, Lasso is a great tool for filtering out the unnecessary features. With all the other factors being the same, we will implement different validation methods to identify the best hyperparameters for each.
