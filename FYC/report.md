# NBA 2019 Championship Predictions - Machine Learning

## Personal Analysis Report

### Using `Winning Rates` as a predicator
* The model was evaluated using `Linear Regression`. The training and testing scores are almost 1.00.

![Residual plot](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_Model_Img/01_LinearRegression.png?raw=true)

* [Script link: Linear Regression](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/01_Linear_Regression_winning_rate_predictions.ipynb)

### Using `WINorLOSS` as a predicator
* `Random Forest` model suggests `Team points` and `Opponent Points` are the most important facotrs.

![RF bar plot](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_Model_Img/02_RandomForest_bar.png?raw=true)

* `SVM` and `KNN` models
      
   * The test accuracies are 1.00 in `SVM` and 0.93 in `KNN` models.
      
* [Script link: RF](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/02_Random_Forest_win_lose_predictions.ipynb)
* [Script link: SVM and KNN](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/03_SVM_KNN_win_lose_predictions.ipynb)

### Using `Team` as a predictor
* The models were evaluated using `RF`, `Logistic Regression`, `SVM` and `KNN`. None of these can have satisfactory testing scores or accuracies.

* [Script link: RF Model 1](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/06_Random_Forest_team_predictions.ipynb)
* [Script link: RF Model 2](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/07_Random_Forest_team_predictions.ipynb)
* [Script link: Logistic Regression](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/04_Logistic_Regression_team_predictions.ipynb)
* [Script link: SVM and KNN](https://github.com/arcebri1/FinalProject/blob/fyc_analysis/NBA_ML_Scripts/05_SVM_KNN_team_predictions.ipynb)

### Summary
Using `Winning Rates` and `WINorLOSE` outcome as predictors are more accurate than using `team` in this project. In order to build a model to predict the 2019 champion using `team`, more variables should be incorporated or calculated to predict the appropriate models.

### Abbreviations
* RF: random forest
* SVM: support vector machine
* KNN: k-nearest neighbors 

### Data Resources
* [http://nba.com](https://www.nba.com/stats/teams/traditional/?PerMode=Totals&sort=TEAM_NAME&dir=-1&Season=2013-14&SeasonType=Regular%20Season)
* [Kaggle Dataset: NBA Team Game Stats from 2014 to 2018](https://www.kaggle.com/ionaskel/nba-games-stats-from-2014-to-2018)