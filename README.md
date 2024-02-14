# Sales Forecasting

Status: IN PROGRESS

Source: [Store Sales TS Forecasting - A Comprehensive Guide](https://www.kaggle.com/code/ekrembayar/store-sales-ts-forecasting-a-comprehensive-guide/input?select=transactions.csv)

Learning Objective:
*  Interpolation for Oil Prices
* Detailed Data Manipulation for Holiday and Events Data
* Exploratory Data Analysis
* Hypothesis Testing
* Modelling

Introduction:
This competition is about time series forcasting for store sales. The data comes from an Ecuador company as known as Corporación Favorita and it is a large grocery retailer. Also, the company operates in other countries in South America.

There are 54 stores and 33 prodcut families in the data. The time series starts from 2013-01-01 and finishes in 2017-08-31. The dates in the test data are for the 15 days after the last date in the training data.

Datasets:
* Train: time series of the stores & product families combination. The sales column gives the total sales for a product family at a particular store at a given date.
* Test
* Store
* Transactions: number of transactions made per store per day
* Holidays and Events
* Daily Oil Price: since Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices. This data will help understand which product families are positively or negatively affected by oil price.


Additional notes:
* Wages in the public sector are paid every two weeks on the 15 th and on the last day of the month. Supermarket sales could be affected by this.
* A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.
