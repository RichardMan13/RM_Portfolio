# Ricardo Junior Firoavante - Portfolio

## [1. Credit Card Fraud Detection](https://github.com/RichardMan13/credit_card_fraud_detection)

* Created a model for prevent fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
* The data was acquire in kaggle.com(see the code references).
* Undersample technique was used for treat the unbalanced data and compare without using the technique.
* Logistic Regression using GridsearchCV to reach the best model.
* The model reach a recall score of **0.96** on the test data, against **0.61** without undersample.

### Confusion Matrix on Undersample test data
![Confusion Matrix on Undersample test data](/images/cm_1.png)
### ROC Curve on Undersample test data
![ROC Curve on Undersample test data](/images/roc_1.png)

## [2. System Of Predictions On Real Estate ](https://github.com/RichardMan13/system_of_predictions_on_real_estate)

* Created a model for predict the price of real estates
* The data was scraped using scrapy on [imobiliariaativa](https://www.imobiliariaativa.com.br) website and saved using postgresql.
* A EDA was made using jupyter notebook for features selection.
* The mlflow was use for Linear Regression model witch reach a R2 of **0.86** and RMSE of **188252.95**.

### Scatter Plot Of Predictions Against Real Values
![Scatter Plot Of Predictions Against Real Values](/images/pred_vs_real_values.png)
