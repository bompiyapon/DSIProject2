# DSI Project 2 (DSI Project 2 Regression Challenge)


This notebook analysis Aimes House sale prices. The data is show as the price in Aimes, lowa. The data contains more than 80 features to evaluates house sale prices.

### Problem Statement: 

I am a agency of consultant company which give an advice to the real estate company which looking for building new house and do interior / outerior decoration for sale .To increase their sell price of the house to maximize their profit, I will find out which factor they need to focus in order improve the Sale price of the house. And I will also generalize model of prediction to see is it can modelize to another city or not.

In case they have limited budget I will help them to focus on the feature / quality to maximize their profit the most

### About the file:

in folder dataset:
train.csv - 80 features with the sale price [81 columns in total] / 2051 house sale records 
test.csv - 80 features without the sale price. This file use to predict and submit on kaggle to determine score [url: https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/overview]

DSI_project2_ver4.ipynb - This file contain the process of doing analysis [read file / EDA / clean data / create model / visualization / conclusion & suggestion] step by step

KaggleScore.JPG - show score for submission on Kaggle

submission file:
  - contain 5 versions from different model which predict from the file test.csv to submit to kaggle

### Conclusion:

The reason why I use lasso model because it's work better on unseen data as you can see on RMSE test score of the lasso is least. And the model is quite not overfitting

Recommendation for real estate agent for building new house and decorate it

Build house in 5 this area. Stone Brook, Northrdige Heights, Northridge, Green Hill, Veenker
Having a big area of living
Focus on building kitchen with good quality will significantly increase the saleprice of the house
Don't use Clay or Tile as a roof material will significantly drop the price. Others material are fine don't have a big different effect on sale price.
Should avoid building dwelling type of Townhouse End Unit will drop the house sale price.
