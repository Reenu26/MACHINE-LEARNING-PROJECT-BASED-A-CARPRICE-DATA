# MACHINE-LEARNING-PROJECT-BASED-ON A-CARPRICE-DATA
In this work we use a data set based on price of cars to analyse  which variables are significant in predicting the price of a car and How well those variables describe the price of a car Based on various market surveys. we have a large dataset of different types of cars across the American market.
first step is loading data and preprocessing which include checking null values, duplicate values etc. as it is found zero duplicate and null values we further proceed to next step
use describe function to display mean ,median,mode and observed skewness.it is treated with iqr method
next step is encoding and scaling 
impliment different models which are linear regressor,DecisionTreeRegressor,RandomForestRegressor,GradientBoostingRegressor,svr
gradient boosting regressor is considered as the best fitting model here because of high r2 and low mean sqaured error and mean absolute error.RandomForestRegressor also performed well.
by drawing pyplot we found among the all independant features curbweight is considered as the important to calculate a car price.
also the other features differ in values as follows

('curbweight', 0.46388524365983935),
 ('horsepower', 0.21007119931423385),
 ('carwidth', 0.05731672707008461),
 ('citympg', 0.05407912892093768),
 ('highwaympg', 0.04221426228347965)]
