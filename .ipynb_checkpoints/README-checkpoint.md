# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The project aims to develop a statistical model to understand how the number of bikes at a selected location correlates with the attributes of Points of Interest in the same vicinity.

## Process
Step 1: Connection to CityBikes API and exploration of the structure of the API in order to retrieve Bike Station latitude, longitude, and number of bikes for chosen location.

Step 2: Connection to Foursquare API and exploration of the structure of the API in order to retrieve information for restaurants and bars for each of the bike stations from step 1.

Step 3: Connection to Yelp API and exploration of the structure of the API in order to retrieve information for restaurants and bars for each of the bike stations from step 1.

Step 4: Joining of data from step 1, step 2 and step 3 into a new DataFrame.

Step 5: Use of data visualization to explore the data.

Step 6: Creation of SQLite database to store the data collected.

Step 7: Building of regression model to show relationship between number of bikes and places of interest in the location.

Step 8: Interpretation of results and presentation of findings.

## Results
For the city of Manchester, while analyzing the relationship between the availability of bikes and local Points of Interest (POIs), the data from the Foursquare and Yelp API provided a comprehensive set of attributes for each POI, enhancing the quality of the analysis.

The constructed model, however, indicates a relatively weak statistical relationship between POI characteristics and the number of free bikes at a given station. The low R-squared value, alongside a negative adjusted R-squared, suggests that the model's independent variables explain only a small fraction of the variance in the number of free bikes. This points to the possibility that other unexamined factors might play a more significant role in influencing bike availability in Manchester.

## Challenges 
The Yelp API daily limit was a challenge. Had to change the city to accommodate for the API daily limit. 

## Future Goals
Analyse data from different cities and times would give richer data insights to enhance the model.
