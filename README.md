# Churn-Prediction-Boosting
- Customer churn (commonly known as customer attrition) occurs when customers stop doing business with a company. The companies are interested in identifying trends of these customers because the price for acquiring a new customer is usually higher than retaining the old one. 
- For the purpose of this project, I look into ride share service customer data with the objective of predicting churn and implement an ensemble boosted tree model and look at confusion matrix to assess model performance.

# Description of data
- Since the data is sourced from a real company, I am unable to provide the raw files. However, here is a detailed description of the data just to give an overview of what we are going to be working with

- `city`: city this user signed up in phone: primary device for this user
- `signup_date`: date of account registration; in the form `YYYYMMDD`
- `last_trip_date`: the last time this user completed a trip; in the form `YYYYMMDD`
- `avg_dist`: the average distance (in miles) per trip taken in the first 30 days after signup
- `avg_rating_by_driver`: the rider’s average rating over all of their trips 
- `avg_rating_of_driver`: the rider’s average rating of their drivers over all of their trips 
- `surge_pct`: the percent of trips taken with surge multiplier > 1 
- `avg_surge`: The average surge multiplier over all of this user’s trips 
- `trips_in_first_30_days`: the number of trips this user took in the first 30 days after signing up 
- `luxury_car_user`: TRUE if the user took a luxury car in their first 30 days; FALSE otherwise 
- `weekday_pct`: the percent of the user’s trips occurring during a weekday

# Outline of project (more details in Jupyter Notebook)
- Data processsing and EDA
- Boosted tree modeling
- Feature importances
- GridSearch and Bayesian hyperparameter optimization
- Data-driven recommendation to company
