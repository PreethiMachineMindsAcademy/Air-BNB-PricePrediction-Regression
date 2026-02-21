# Airbnb-price-prediction-regression

### Problem Statement
Let’s say we want to build a model to predict booking prices on Airbnb. Between linear regression and random forest regression, which model would perform better and why?

We used the dataset from Kaggle [https://www.kaggle.com/datasets/tahirelfaki/airbnb/data] for the regression models. We also included XGBoost Regression model to compare among the two other models to determine which one worked the best.

### Data Dictionary
1. id: Property ID
2. room_type: Type of Room in the property
3. accommodates: How many adults can this property accomodate
4. bathrooms: Number of bathrooms in the property
5. cancellation_policy: Cancellation policy of the property
6. cleaning_fee: This denotes whether the property's cleaning fee is included in the rent or not
7. instant_bookable: It indicates whether an instant booking facility is available or not
8. review_scores_rating: The review rating score of the property
9. bedrooms: Number of bedrooms in the property
10. beds: Total number of beds in the property
11. log_price: Log of the rental price of the property for a fixed period
