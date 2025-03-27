# Car-Price-Prediction
## Objective
The objective of this project is to model the price of cars using the available independent variables. This model will help the management understand how car prices vary with different features, allowing them to manipulate car designs and business strategies to meet specific price levels. Additionally, the model will provide insights into the pricing dynamics of a new market.
#### Linear Regression:
##### Description: 
This model assumes a linear relationship between the input features and the target variable. It fits a straight line (or hyperplane in higher dimensions) to the data.
Performance: In this case, it had a high Mean Squared Error (MSE) and a negative R2 score, indicating poor performance.
#### Decision Tree Regressor:
##### Description: 
This model splits the data into subsets based on feature values, creating a tree-like structure. Each leaf node represents a predicted value.
##### Performance: 
It performed well with a low MSE and a high R2 score, indicating good predictive accuracy.
#### Random Forest Regressor:
#### Description:
This ensemble model combines multiple decision trees to improve accuracy and reduce overfitting. It averages the predictions of individual trees.
##### Performance:
It had the best performance among the models, with the lowest MSE and the highest R2 score.
#### Gradient Boosting Regressor:
##### Description:
This ensemble model builds trees sequentially, with each tree correcting the errors of the previous ones. It optimizes the model by minimizing a loss function.
##### Performance: 
It also performed well, with a low MSE and a high R2 score, though slightly lower than the Random Forest Regressor.
#### Support Vector Regressor (SVR):
##### Description: 
This model uses support vector machines to find a hyperplane that best fits the data, with a margin of tolerance for errors. It can model non-linear relationships using kernel functions.
##### Performance:
It had a high MSE and a low R2 score, indicating poor performance for this dataset.
#### Feature Importance Analysis
Identify Significant Variables: Use a Random Forest Regressor to determine which features most affect car prices. The model calculates feature importance based on how much each feature reduces variance in the data.
#### Hyperparameter Tuning
Optimize Model Performance: Perform Grid Search to find the best combination of hyperparameters for the Random Forest Regressor. Evaluate the tuned model using metrics like Mean Squared Error (MSE) and R2 score to check for performance improvements.
## Conclusion
This project involves loading and preprocessing the car price dataset, implementing multiple regression models, evaluating their performance, analyzing feature importance, and performing hyperparameter tuning to improve the model's performance. The best performing model will provide valuable insights into the factors affecting car prices, helping the management make informed decisions.
