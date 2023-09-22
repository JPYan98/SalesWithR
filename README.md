# Time Series Analysis and Transaction Prediction

## Abstract
The report encompasses an in-depth analysis of a dataset representing marketing and sales transactions conducted over a specific period. The aim is to perform a time series analysis, employing various statistical and machine learning techniques, to predict daily revenue and understand the dynamics of transaction occurrences through logistic regression and decision tree models.

## Objectives
1. To forecast daily revenue through time series analysis.
2. To predict transaction occurrences based on several factors like page visits, product clicks, and checkout actions.

## Methodology
### Data Preparation:
1. The dataset was obtained from Kaggle, encompassing 14 columns representing various transaction attributes.
2. The dataset was read into R and pre-processed to ensure quality and consistency for analysis.

### Time Series Analysis:
1. Utilize ARMA and ARIMA models to analyze and predict daily revenue.
2. Normalize the data to mitigate the effects of large values.
3. Forecast future daily revenues using the ARIMA model.

### Transaction Prediction:

1. Created a binary response variable to represent whether a transaction occurred or not.
2. Split the data into training and test sets to validate the models.
3. Implemented a Logistic Regression model and evaluated it using accuracy and AUC.
4. Implemented a Decision Tree model and evaluated it against the Logistic model.

## Results
### Time Series Analysis:

1. The ARIMA(12,1,1) model provided a reliable forecast for daily revenue.
2. The prediction conformed to previous fluctuation laws, demonstrating a satisfactory fit to the data.
### Transaction Prediction:

1. The Logistic model achieved an accuracy of 86.05% and an AUC of 0.93 on the test data.
2. The Decision Tree model slightly outperformed the Logistic model with an accuracy of 86.77%, albeit with a lower AUC of 0.8.

## Discussion
The report revealed significant insights into the factors affecting transaction occurrences. It was observed that variables such as visits, product clicks, checkout actions, and the marketing medium significantly influenced the likelihood of transactions. However, some platforms and mediums yielded a more significant impact than others. The time series analysis and forecasting provided a robust understanding of daily revenue trends, crucial for future marketing and financial planning.

## Conclusion
The analysis rendered a comprehensive perspective on the transactions dynamics and revenue trends. The methodologies employed could further be refined or extended for more nuanced insights or longer-term forecasts. These findings are pivotal for shaping marketing strategies, financial planning, and enhancing customer engagement to foster a higher transaction rate.

## Dependencies
1. R (version 3.6.3 or later)
2. Required R libraries: tidyverse, forecast, caTools, pROC, tree, texreg.


The source of the dataset is: https://www.kaggle.com/datasets/denis6715/marketing-sales

The final version of the R code is missing due to a broken PC. The final code will be uploaded once it has been repaired. However, Version 1 of the R code is already complete enough.
