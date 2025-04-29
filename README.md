# BUA451-FinalProject-Ben-Fall (README)

# Project Overview
This project analyzes tipping behavior in New York City Yellow Taxi rides using 2018 trip data obtained from Google BigQuery. The goal was to perform exploratory data analysis (EDA) and build predictive models to estimate whether a passenger would leave a tip based on trip characteristics.

The project involves:

SQL querying from Google BigQuery

Data cleaning and feature engineering

Exploratory data analysis with visualizations

Building classification models (Logistic Regression, Decision Tree, Random Forest)

Drawing business insights and managerial recommendations


# Dataset Information

Source: BigQuery Public Data – NYC Yellow Taxi Trips 2018

Table: bigquery-public-data.new_york_taxi_trips.tlc_yellow_trips_2018

Sample Size: 10,000 rides extracted via SQL

# Key Variables Used:

- trip_distance: Distance of the trip in miles
- fare_amount: Fare charged (excluding tip)
- tip_amount: Tip given by the passenger
- passenger_count: Number of passengers
- pickup_datetime: Time the trip started
- payment_type: Method of payment


# Key Findings:
Tip rates increase with trip distance and fare amount. Peak taxi demand occurs between 2 PM and 6 PM. Credit card payments are associated with a higher likelihood of tipping. A Random Forest model achieved approximately 60% accuracy in predicting tipping behavior based on basic trip features.
