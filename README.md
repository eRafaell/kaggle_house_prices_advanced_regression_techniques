### Kaggle - House Prices Advanced Regression Techniques
Competition Website: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

#### Competition Description
> Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

> With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

From the competition [link](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

#### Goal
For each Id in the test set, you have to predict the house sales price value. SalePrice is the target variable to predict.

#### Used models and scores

| Model | RMSE | R2 score |
| ------ | ------ | ------ |
| XGBoost | 0.115915 | 0.909652 |
| GradientBoosting | 0.124432 | 0.895888 |
| RandomForest | 0.143895 | 0.860771 |
| ElasticNet | 0.147107 | 0.854486 |
| Ridge | 0.176292 | 0.79102 |
| DecisionTree | 0.201165 | 0.727891 |
| Lasso | 0.208516 | 0.707641 |

#### Metric
Submissions are evaluated on Root Mean Square Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

#### Conclusion
The best model in this Notebook is XGBoost, which can make 0.1159 RMSE prediction error for a house price.
