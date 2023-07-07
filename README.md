# PubG-Game-Prediction
PubG game Winning Prediction based on CatBoost Model

Dataset - ![Kaggle - Pub g Game Dataset](https://www.kaggle.com/datasets/ashishjangra27/pubg-games-dataset)

In the project "PubG Game Winning Prediction," a CatBoost model was used along with RMSE (Root Mean Square Error) and Grid Search techniques. The goal of the project was to predict the winning placement percentile for players in the game PlayerUnknown's Battlegrounds (PUBG). 

The CatBoost model is a gradient boosting algorithm specifically designed to handle categorical features. It was used to train a predictive model using the provided dataset. The model was evaluated using RMSE, which measures the average difference between the predicted and actual values. In this case, the RMSE value obtained on the testing dataset was 0.08.

Additionally, the R2 (R-squared) metric was calculated, which represents the proportion of the variance in the target variable that can be explained by the model. A value of 0.93 indicates that the model explains approximately 93% of the variance in the winning placement percentile.

Grid Search was employed to optimize the hyperparameters of the CatBoost model. This technique systematically searches through a specified set of hyperparameter values to find the best combination that yields the highest performance.

Overall, based on the testing performance, the CatBoost model achieved a low RMSE value of 0.08, indicating that it was able to make accurate predictions of the winning placement percentile in the PUBG game. The high R2 value of 0.93 suggests that the model is a good fit for the data, as it explains a significant portion of the variance in the target variable.
