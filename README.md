# AlphaZero
Datathon Team
data cleaning - exploratory data analysis to check for outliers, missing data, and explore the statistics and distribution
we compared each of our features against our label which is our rate of penetration

once we cleaned the data and removed the outliers, we used a standard scaler in our data preprocessing step to scale our data 

so for example, our features (x) contain all the quantitative variables except for categorical variables 
and our label (y) is the "rate of penetration"

moving forward, we used kfold cross validation to check our model performance, fitting the model with light gradient boosting method regressor
to increase our performance, we did hyperparameter tuning using hyper opt which is a library for bayesian optimization. 

As a result we got an RMSE on average of less than 10 on train, and less 25 on validation.
