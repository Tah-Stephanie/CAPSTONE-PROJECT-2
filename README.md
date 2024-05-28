# RESTAURANT RATINGS DASHBOARD
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT-2/blob/main/Restaurant%20ratings.png)

# Introduction
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT-2/blob/main/Restaurant%20rating%20dashboard.png)

This Power BI project is a capstone project which  aims at analysing data collected from different restaurant ratings from unknown restaurants in Mexico. A customer survey was carried out in this city in 2012 to collate information about each restaurant, their cuisines, information about their consumers and the preferences of the consumers. The project report answered all the business questions which will in turn help in drawing out meaningful insight from the restaurant rating dataset which would aid management in making informed decisions to improve performance and profitability. 

## Problem statement

Question 1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?

 Question 2. What are the consumer demographics? Does this indicate a bias in the data sample?

 Question 3. Are there any demand & supply gaps that you can exploit in the market? 

Question 4. If you were to invest in a restaurant, which characteristics would you be looking for?

## Skills and concepts demonstrated

The following skill sets were used: 
Data cleaning
 Data transformation
 Data Modelling
 DAX
 Filters
 Power Query
 Data Visualization

## Modelling

The sourced dataset had 5 tables, With 3 fact tables and two dimension tables.
An automatic relationship was developed by power bi between two fact tables and two dimension tables.
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT-2/blob/main/Original%20model%20with%20automatically%20built%20relationships.png) Original model


Using data modeling techniques a bi-directional crossfilter relationship was developed between the consumer preference fact table and the consumer dimension table. A bi-directional relationship was also created between different tables to link them.
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT-2/blob/main/Modified%20model.png) Modified  Model

The model type is a galaxy schema because we had one dimension table linked to one fact table. The 2 other fact tables did not have any active relationship and were also not useful for our analysis.

## Visualisations
The report is made up of 1 page which answers the 4 business questions

## Features
The 3 slicers are used to filter our report according to age group and city for better understanding.

## Analysis:

### Preliminary Data Analysis
![](https://github.com/Tah-Stephanie/CAPSTONE-PROJECT-2/blob/main/Preliminary%20Data%20analysis.png)

The number of consumers equal 138
Number of cuisines equal 23
Number of cities equals 4
Number of restaurants equal 127
The average age of all customers equals 27

### Analysis of cities with the highest rated restaurants
![]()

San Luis potosi stands out for having the top-rated restaurant with total ratings of 395
Cuernavaca ranks second in terms of its highly rated restaurants, boasting an impressive total rating of 57

Cuidad victoria ranks third in terms of its highly rated restaurants, boasting an impressive total rating of  28

Juitepec stands at the bottom of the list for its highly-rated restaurants, with a remarkable overall rating of 9

### Analysis of the effects of ratings by consumer preferences
![]()

This was obtained using the bi-directional crossfilter relationships developed between the consumer dimension table and the consumer preference and ratings fact tables. This relationship was used to link the consumer preference fact table and the ratings fact table. From this, the overall rating of each preferred cuisine rated by each consumer could be gotten.

The visual shows the preferred cuisines of consumers in an ascending manner with Mexican cuisine being the highest preferred cuisine.

### Analysis of consumer demographics 
![]()

There is  bias in the distribution of customers as most of the customers are found in the city of  San Luis potosi with a total of 92 customers.

### Analysis of the demand and supply gaps
![]()

This analysis was done by comparing the different age groups of all customers in the different cities. The different age groups were divided as follows:

Young adults 18-30
Middle-aged adults 31-45
Old-age adults 46 and above 

The analysis reveals that the majority of consumers are young adults. These young adults are distributed throughout all cities, with the highest concentration in San Luis Potosi.


### Analysis of the characteristics to look at when planning to invest in a restaurant
![]()

This analysis is a result of examining the most popular cuisine in various cities and the number of consumers who have a preference for each cuisine.

It can be seen that the mexican cuisine has the highest number of ratings in the city of San luis potosi which has the highes number of consumers.

# Conclusion
From the different reports it can be concluded that San Luis Potosi is the city with the higest number of consumers and the most rated cuisine is the Mexican cuisine hence should be a cuisine for many restaurants. 
