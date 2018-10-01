# **Suggesting cities with popular restaurant type**
## Introduction
Given a particular restaurant type, we are going to output the cities that are interested in that particular type of restaurant.
Investors and businessmen looking to open restaurants in a particular city would find this information useful as they can see what is the city's interest in a particular cuisine and what type of restaurant would bring maximum profit.
When a particular cuisine or restaurant type is given as an input to the system, the system would output the cities in the United States of America that are most likely interested in this type of cuisine or restaurant type.
This information can help a lot of businessmen and small businesses to establish their restaurants based on the most popular cuisine. It would also help franchises to open a chain or modify their menu based on the likings of the people there in that particular area. It would also be helpful in estimating the popularity of a cuisine in the country.

## Data
There were two types of data used:
1. ***Foursquare***
  This was mainly used to get all the popular venues of the city to determine the most popular restaurant type in the city. Since a lot of calls were made to fourquare, it was hard to get all the venues again and again and had to wait for the next day to get the result of the  code written.
2. ***Kaggle***
  _(https://www.kaggle.com/mahbubrob/usa-cities#usa_cities.csv)_
  This was mainly used to get the list of cities in the United States of America to get the data from foursquare.
These data together were combined to fine the final result that was mentioned earlier.

## Methodology
The aim was to give the list of cities interested in a particular type of cuisine. Hence we needed Kaggle USA cities data to collect information about all the cities and foursquare data to get the restaurant data for all these cities.
So there were four steps to it:
- Get city data
- Get foursquare data for these cities and store
- Take the input from the user for the type of restaurant
- Check which cities have this restaurant type as the most popular
