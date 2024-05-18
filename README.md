# AirBnB-prices-prediction

In this analysis we need to predict the fair value a host should ask based on different atributes given below. Based on the prediction, the airbnb can ask the host if he is charging less or more.


1. The owner has been a host since **August 2010**
1. The location is **lon:151.274506, lat:33.889087**
1. The current review score rating **95.0**
1. Number of reviews **53**
1. Minimum nights **4**
1. The house can accomodate **10** people.
1. The owner currently charges a cleaning fee of **370**
1. The house has **3 bathrooms, 5 bedrooms, 7 beds**.
1. The house is available for **255 of the next 365 days**
1. The client is **verified**, and they are a **superhost**.
1. The cancelation policy is **strict with a 14 days grace period**.
1. The host requires a security deposit of **$1,500**


*All values strictly apply to the month of July 2018*

The code is about data preprocessing and training a machine learning model to predict the price of a property based on various features. It starts with loading the data from a CSV file and performing exploratory data analysis to understand the distribution of the features and identify any missing values or outliers.

The code then cleans the data by imputing missing values and encoding categorical features. It also creates new features based on existing ones, such as bedrooms per person and bathrooms per person.

Next, the code splits the data into training and test sets and trains a linear regression model to predict the price. The model is then evaluated on the test set using mean squared error and mean absolute error.

The code then explores other models such as decision trees, random forests, and support vector machines. It performs hyperparameter tuning using grid search and randomized search to find the best model parameters.

Finally, the code uses the best model to predict the price of a new property based on the user-specified features.

The code is well-structured and uses a variety of techniques to clean and prepare the data, train and evaluate the model, and make predictions. It also provides detailed comments and explanations for each step of the process.
