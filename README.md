# House-Price-Prediction-Problem
The aim of this model is to predict the house prices with the greatest accuracy by considering the RMSE and R2 square values.
Algorithms used Linear Regression, Decision Tree

Steps-
1. Initially we have imported the training data and necessary libraries.
2. By analysing the dataset we first question the data and create some initial hypotheses.
3. Then we did Exploratory Data Analysis on data and found some suprising results.
4. We took some set of predictors for Multiple linear Regression.
5. After doing 10-fold split on it we report our Rmse and r^2 for the values.
6.Then we tried Feauture generation on the predictors (dummy variables, create a variable age using other set of predictors such as date & yr_built).
7.Feature transformation:log and square root transformation because its a skewed data for predictors.
8.Forward selection through Regression : using mlxtend library [scoring='r^2]. For every step doing a 10-fold cv split and recording RMSE and r^2.
9. DECISION TREE- We tried the same set of predictors on Decision tree model using the best hyperparameters.
10.From all the models we fit our data through , we select the best model based on the performance metrics we took and use them to predict the prices of the test_data.
11 .We report our prices.
