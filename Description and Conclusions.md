## Information about the data set:Rental prices- data analysis 
A dataset from a A housing rental company includes details about each property rented, Number of bedrooms, Number of bathrooms, as well as the price charged per night is provided. Data analysis of the the given data is done to answer the follwing questions:
1-What are main factors affect rental price?.
2-Do number of bathrooms has significant effect on price?.
3-Are there certain property or room types that have higher rental prices?

## A summary steps taken in your analysis:
Table of Contents
Introduction
Data Wrangling
Statstical Approach
Exploratory Data Analysis
Regression Model
Conclusions

## Key points discovered in your exploratory file:
From previous exploratory data analysis and supervised machine learning model we can conclude the follwoing conclusion:

1-bedrooms have the higest effect on rental peice, followed by the minimum nights.
2-There is a linear relation between price, and numerical features except for the bathrooms that is replaced by the interaction term of bathrooms multiplied by bedrooms, actualy we don't need bathrooms in our model, also there is no multimulticollinearity.
3-Price distribution is skewed, most common prices are under 20000$.
4-Most popular rentals have only one to two bathrooms.
5-Most popular rentals have only one to two bedrooms.
6-Most of rentals are month rentals, follwoed by few 2 to 3 days rentals.
7-Most common room and property type are the apartment type for both the room and the property.
8-There is a relationship between price and property types of Resort, Villa, Earth house, and the room type of Entire home/apt as they have 9-the higest mean prices.
10-The two combinations of Entire home/apt and villa have the higest prices.
11-The Entire home/apt was the room type was the only one to increase in price when bathroom and bedroom numbers increases.
While building this model, we tackled some of the most widely-known preprocessing steps such as scaling,dummy variables. We finished with some machine learning to predict the price. the top important features were bedrooms, minimum nights, bath_bed rooms ,and property type of twon house.
