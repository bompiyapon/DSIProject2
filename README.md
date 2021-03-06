# DSI Project 2 (DSI Project 2 Regression Challenge)


This notebook analysis Aimes House sale prices. The data is show as the price in Aimes, lowa. The data contains more than 80 features to evaluates house sale prices.

### Problem Statement: 

I am a agency of consultant company which give an advice to the houseowner to increase their sell price. And also real estate agent or broker who looking to investing to build houses and sold to make profit. I will find out which factor they need to focus in order improve the Sale price of the house. And I will also generalize model of prediction to see is it can modelize to another city or not.

### About the file:

in folder dataset:
train.csv - 80 features with the sale price [81 columns in total] / 2051 house sale records 
test.csv - 80 features without the sale price. This file use to predict and submit on kaggle to determine score [url: https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/overview]

DSI_project2_ver4.ipynb - This file contain the process of doing analysis [read file / EDA / clean data / create model / visualization / conclusion & suggestion] step by step

KaggleScore.JPG - show score for submission on Kaggle

submission file:
  - contain 5 versions from different model which predict from the file test.csv to submit to kaggle

### Conclusion:

The reason why I use lasso model because it's work better on unseen data as you can see on cross_val score. Although RMSE of train model is a bit better but lasso do a better performance on prediction on unseen data

In my opinion these model are generalize. As you can see from the lasso coefficient which top feature that effect the sale price is very general. Only the neighborhood that is specific in this city. However, I think it can be adapt neighborhood with the location in other city.

About the error of prediction is around 21,000 - 22,000. Therefore, this model works great on the price between 3,560 - 340,000 dollars (approximately). If it's out of this range the error of price prediction will increase and prediction can be far from the actual price. (As I do the outlier the price of this range can do a wrong decision)
