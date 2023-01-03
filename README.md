# ML Trading Bot
![image](https://user-images.githubusercontent.com/107276527/198450795-851e7b0b-1e82-4db5-aa0c-deb53e1f2d69.png)

Project 2 Submission - October 2022

## Team Members
- David Garcia 
- Shay Schreurs
- Tim L.
- Arandi M.

## Motivation

- Our motivation was to apply machine learning techniques to develop an algorithmic trading bot. A machine learning model was used to attempt to accurately predict the right time to buy or sell a stock. The core idea was to efficiently make profitable trades in the stock market.

## Data Preparation & Model Training
- Data Preparation:
  - Determine variables (X data) and the target (y)
  - Is the data balanced?
  - Train data using different models
- Model Evaluation
  - Use test data to evalaute model performance
- Predictions
  - Make predictions using the best performing model
- Data Visualization 
  - Visualize the results 
- Make Money!!! (We hope)


# Machine Learning Models

- Three machine learning models were utilized to train and predict the trading data sourced from [Alpaca API](https://paper-api.alpaca.markets). The target was determined to be the entry price plus 3 times the Average True Range(ATR): '1'. The stop was determined to be the entry price minus the Average True Range (ATR): '-1'. Support Vector Machine (SVM) and Decision Tree models learnt in class were applied to this data. We used Stochastic Gradient Descent (SGD) for the new model as stipulated in the project requirements. 

- The data was prepared by ascertaining performance indicators and the target. The data was then scaled and undersampled to ensure the data is balanced before training. The best perfoming model from the evaluations is then selected for predictions.

## Technologies
- Jupyter lab
- Python
- Pandas
- Numpy
- Pyviz
- finta 
- Scikit 
- pydotplus
- Google Collab


## Outcomes
- For the initially selected stocks, the SVM model performed the best. However, as this is a dynamic bot, this may change depending on the selected security and the time periods among other factors that the user may determine to apply.
