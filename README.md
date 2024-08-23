# Rossmann-Store-sales-prediction-ML-Project
There are two datasets, Rossmann store dataset and the store data set. Rossmann store dataset contains 1017209 rows and 9 columns without duplicate data and null values. Store dataset contains 1115 rows and 10 columns without duplicate data and some null values in columns CompetitionDistance, CompetitionOpenSinceMonth,CompetitionOpenSinceYear, Promo2SinceWeek, Promo2SinceYear, PromoInterval. After treating the null values and doing feature engineering we got below results.

In this project, a Random Forest machine learning model has been selected as the final model for predicting sales. Here's a brief summary of the key findings and the project's status:

Model Selection:

The Random Forest machine learning model has been chosen as the final predictive model due to its outstanding performance. The model achieved a high training accuracy of 99.60%, indicating a strong fit to the training data. The model's test accuracy is 97.26%, which suggests that it performs exceptionally well on unseen data, demonstrating its reliability for future predictions.

Root Mean Squared Error (RMSE):

The root mean squared error is impressively low, with a value of 516.18, indicating that the model's predictions are very close to the actual sales values.

Project Objective:

The primary goal of this project is to build a predictive model capable of forecasting sales. By achieving high accuracy and low root mean squared error, the Random Forest model has demonstrated its potential to provide accurate sales predictions, which can be valuable for optimizing inventory, staffing, and other operational decisions for the Rossmann stores in the future.

Problem Statement
Rossmann operates a network of more than 3,000 drug stores across seven European countries. At present, store managers at Rossmann are responsible for forecasting their daily sales for a period of up to six weeks in advance. These sales predictions are affected by a multitude of factors, such as promotional activities, competitive factors, school and public holidays, seasonal patterns, and the specific location of each store. Given the diverse set of conditions that each store manager faces, the accuracy of these sales predictions can vary significantly.

Data Description
rossman.csv - historical data including sales

store.csv - supplimental information about the store

Store - a unique Id for each store

Sales - the turnover for any given day (this is what you are predicting)

Customers - the number of customers on a given day

Open - an indicator for whether the store was open: 0 = closed, 1 = open

StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None

SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools

StoreType - differentiates between 4 different store models: a, b, c, d

Assortment - describes an assortment level: a = basic, b = extra, c = extended

CompetitionDistance - distance in meters to the nearest competitor store

CompetitionOpenSince[Month/Year] - gives the approximate year and month of the time the nearest competitor was opened

Promo - indicates whether a store is running a promo on that day

Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating

Promo2Since[Year/Week] - describes the year and calendar week when the store started participating in Promo2

PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store
