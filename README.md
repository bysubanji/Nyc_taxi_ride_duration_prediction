# Nyc_taxi_ride_duration_prediction
              
# PROBLEM STATEMENT
In this task is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

# APPROACH
In first step, imported the data set to carry out the descriptive analysis over the data set to understand the information of data available.

Checked for missing and repetition of values in the data set provided.

Exploring all the variables of the data set (such as Vendor-Id, Pickup_point, Dropoff_point,Distance, Speed, Storage_frwd, etc) with respect to trip duration, to determine the factors and understand factors of trip duration.

Used data visualization with different kinds of plots to explore the correlation with Trip duration and
different variables.

Encoding of categorical columns and fitting the different models, we used below algorithms :-
Lasso Regression
Ridge Regression
Decision tree Regressor
XGBoost Regressor

Then tuning into Hyperparameters and perfomance evaluation to identify best fit Model.

# CONCLUSION
Most of the trips durations took 10-30 mins to complete at a speed range of 10-20 km/h.

Trip duration on thursday is longest among all days.

Highest amount of trips were taken by a single passenger and large group of people travelling together is rare compared to single passenger.

Evenings are the busiest and top among the all.

From February, we can see trip duration rising every month. There might be some seasonal parameters like wind/rain which can be a factor of this gradual increase in trip duration over a period.

Trips taken by both vendors not have much difference.

XGbooster is the best performing model amongst all.
