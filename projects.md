---
layout: page
permalink: /projects/
---

![](/asset/kaggle.png) 

<a href="https://github.com/Santostang/Kaggle-restaurant-visitation-forecasting" target="_blank">**Kaggle Restaurant Visitation Forecasting**</a> - The Kaggle Restaurant Visitation Forecasting competition revolved around taking in a dataset of reservation and visitation data to predict the total number of visitors to a restaurant for future dates. For this competition, I used Python to cleaned and visualized daily visitation data (250K rows) to explore the dataset; generated 80+ engineered features, e.g. lagging visitors (mean, median, max, min) for last 14/28/60/120/180 days. After that, I tried a variety of different supervised learning approaches (KNN, gradient boosting and random forest), but ultimately I ranked top 22% with 0.480 RMSE score by ensembling models of gradient boosting and random forest.

<a href="https://github.com/Santostang/kaggle-titanic" target="_blank">**Kaggle Titanic**</a> - The Kaggle Titanic competition revolved around taking in a dataset of all the passengers in the Titanic, and then predicting whether or not they survived. The features in the dataset included room location, age, gender, etc. For this competition, I used a variety of different supervised learning approaches (SVMs, KNNs, Decision Trees), but ultimately found that a KNN model (where K = 17) got the best accuracy of 78.95%. I used Numpy and Sklearn to help preprocess the data and create the models. 


