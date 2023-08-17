# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
### to determine if there is a relationship between he number of city bikes available and a POI (restaurants) in Mantova 
## Process
#### Send requests to city bikes to get information on bike stations in Toronto
#### Send requests to Yelp and foursquare API for information on points of interests - restaurants
#### Parsed through the returned data and created dataframes
#### Merge 2 dataframes - city bike and yelp
#### EDA process for data visualization 
![image](https://github.com/Ceeyhub/Statistical-Modelling-Project/assets/134983985/577cea36-ed1b-4cc7-aa61-e1572c0fb895)

#### check for correlation between the two dataframes
![image](https://github.com/Ceeyhub/Statistical-Modelling-Project/assets/134983985/3b9068ea-1b0c-4a6b-8256-7578acb26f73)

#### put all result into SQLites and try to validate the data
#### Build a regression model and interpret result
![image](https://github.com/Ceeyhub/Statistical-Modelling-Project/assets/134983985/32088b64-1f4e-4e8b-8379-0ddc85c9a30e)


## Results
#### Yelp provided more information than foursquare - it had data on prices, telephone number to call
#### It was difficult to establish any correlation between the bike stations and POIs in the same location
#### Model was not a good fit as R-squared value was low 
#### P-value for model was 0.000

## Challenges 
#### the Bike stations i explored didnt have a lot of bikes and had a lot of 0 in the data ended up changing the bike station entirely
#### Difficulty in finding a good join to merge the dataframes without having NaN values
#### Time constraints, i spent a lot of the time trying to understand how to get the data out of the APIs

## Future Goals
#### get more POIs data to see if i can create a model with a better fit
#### 

