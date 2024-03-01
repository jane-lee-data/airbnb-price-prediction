# Predicting Airbnb Price
The training data contains 1700 Airbnb listings in Hollywood, CA. 

`latitude`, `longitude` : Location </br>
`Entire home`: 1 if the listing is for the entire home, 0 otherwise</br>
`accommodates`: number of guests accomodated</br>
`bathrooms`,`bedrooms`,`beds`: number of respective features</br>
`cleaning_fee` :  one-time cleaning fee</br>
`minimum_nights`: minimum nights to book</br>
`number_of_reviews`</br>
`review_scores_rating`: review scores rating (out of 100)</br>
`instant_bookable`: 1 if instantly bookable, 0 otherwise</br>
`price` : price($) per night</br>

## Model 1
The least absolute deviations regression problem as a linear program.

## Model 2
Add a constraint to include only three most important variables

## Model 3
Predicts Airbnb listing price using only three variables, where one of the variables is the number of beds.
