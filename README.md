# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
### to determine if there is a relationship between he number of city bikes available and a POI (restaurants) in Mantova 
## Process
#### Send requests to city bikes to get information on bike stations in Mantova
#### Send requests to Yelp and foursquare API for information on points of interests
#### Parse through the returned data and create dataframes
#### Merge 2 dataframes - city bike and foursquare
#### EDA process for data visualization 
#### check for correlation between the two dataframes

## Results
#### Yelp provided more information than foursquare - it had data on prices, telephone number to call
#### It was difficult to establish any correlation between the bike stations and POIs in the same location

## Challenges 
#### the Bike stations i explored didnt have a lot of bikes and had a lot of 0 in the data
#### Errors while parsing through the yelp data
#### Difficulty in finding a common column to merge the dataframes
#### Time constraints, i spent a lot of the time trying to understand how to get the data out of the APIs

## Future Goals
#### put all result into SQLites and try to validate the data
#### Build a regression model and interpret result

