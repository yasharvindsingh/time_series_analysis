# Time series analysis

The repository represents some basic analysis of a time series data (clickStream.csv and transactions.csv)

1) adding_session_id file contains code for basic data manipulation task of adding a session id to all the records. A Session is a window of activity from a user & it ends when there is at least 15 mins of inactivity. The resultant data is stored in the file clickStream_session_id.csv

2) seasonal_analysis file contains code and visualization for the series data in transactions.csv, it contains analysis on all the unique categories of the products and calculates a seasonal score which gives you an idea regarding the seasonality of that category during a time period.
