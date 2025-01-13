# Stock-Price-Prediction

Project Overview

This project utilizes machine learning techniques to predict stock market trends, specifically focusing on Tesla stock price data from January 1, 2010, to December 31, 2017. The goal is to determine whether buying a stock on a particular day would result in a profit by predicting a binary signal (1 for buy, 0 for hold/sell). The project involves data preprocessing, feature engineering, exploratory data analysis (EDA), and training machine learning models to make predictions.


Models Used and Results

1)Logistic Regression
          Training Accuracy: ~51.9%      
          Validation Accuracy: ~54.3%
          Observation: Limited performance but avoids overfitting.

2)Support Vector Classifier (SVC)
          Description: A non-linear classifier using a polynomial kernel.          
          Performance:          
          Training Accuracy: ~47.1%          
          Validation Accuracy: ~44.7%
          Observation: Struggled to capture meaningful patterns.

3)XGBoost Classifier
          Description: A robust ensemble learning model using gradient boosting.
          Performance:
          Training Accuracy: ~96.4%
          Validation Accuracy: ~57.2%
          Observation: Best performing model but prone to overfitting due to high complexity.

Conclusion

Among the models, XGBoost demonstrated the highest accuracy on validation data, highlighting its strength in capturing complex relationships. However, it also showed signs of overfitting. Logistic Regression, while simpler, provided more stable results, albeit with limited predictive power. Future improvements could involve adding external factors like news sentiment and macroeconomic indicators to enhance model performance.

