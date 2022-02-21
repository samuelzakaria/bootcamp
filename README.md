# BOSTON HOUSE PRICE PREDICTION MODEL USING LASSO And RIDGE
In this project, I tried and explored regression model on Boston Data House from Kaggle. The dataset consist of 14 parameters with 506 rows of data.
The complete data set and its definitions, you can download in here :
and i also upload the file on this repository.

The goal of this project is to see which one of the best model to predict the house prices,to understand multicollinearity of independent variabels from the data set,
and understand about the interpretation of coefficient on ridge and lasso regression.

## File Description
1. The Rmd is the Rstudio file that can be run in Rstudio Platform. I used markdown file in order to understand the program step by step
2. Pearson Correlation. png is the pair plot from the data set. I used pearson correlation in order to easily understand correlation 
   between dependent and independents variables.
3. Boston.csv is the data set that i used to create the models.


## Model Description
I used Ridge and Lasso Regression in order to see which one is better to be applied in this data set. I did some trial on lambda.
Lambda was set into 0.01,0.1,1,10 on both regression. From 4 different lambdas, I have to take one of the best from RMSE value from the model
Here is the reference website that i used to learn about the regression:
https://www.datacamp.com/community/tutorials/tutorial-ridge-lasso-elastic-net




