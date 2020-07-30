# In this Project ,I have tried to analyze different factors leading to higher IMDB score.The success of movie is Predicted by its IMDB score.


**Higher the IMDB score,successful the movie is!!**

For this purpose I have used different regression models to predict movie IMDB score and later classified the movie into hit,
average and flop using different classification models.

## The performance of different model:-

|Regression Model|Mean_squared_error|
| --- | --- |
|Simple Linear Regression |0.70|
|SVRegressor Linear|0.72|
|SVRegressor Polynomial|0.93|
|SVRegressor RBF|0.68|
|Gradient Boost|0.43|
|Random Forest|0.45|
|XGBoost|0.40|

|Classification  Model|MisClassifications|Accuracy|Precision|Recall|F1-Score|
| --- | --- | --- | --- | --- | --- |
| Logistic Regression | 190 | 0.75 | 0.47 | 0.40 | 0.41 |
| SVC Linear | 181 | 0.76 | 0.47 | 0.45 | 0.46 |
| SVC Polynomial | 143 | 0.81 | 0.52 | 0.50 | 0.51 |
| SVC RBF | 146 | 0.81 | 0.51 | 0.50 | 0.50 |
| Random Forest | 130 | 0.83 | 0.54 | 0.50 | 0.51 |
| Gradient Boosting | 127 | 0.83 | 0.54 | 0.51 | 0.52 |
| XGBoost | 139 | 0.82 | 0.52 | 0.51 | 0.51 |


