# python-api-challenge
Two scripts were written to do the following:
 
 1. In part one, a python script was written in order to determine the weather of hundreds of cities chosen randomly using a weather api. For each city, the country, latitude, and longitude was determined for location using the API. Each city had then had the following weather data determiend by the API: cloudiness, max temp, humidity, and wind speed. After cleaning the data, mulitple plots were made in order to determine if a correlation exists between city location and the weather data described above. The clean data was then exported to a CSV to be used for part 2.
 
 2.  In part 2, the csv file created in part 1 was used to create a heat map for each city using google api. In addtion to the heat map, markers were created for hotels in the ideal cities and plotted on top of the heat map. Condiditions for the ideal cities were as follows: 
    
    a. A max temperature lower than 80 degrees but higher than 70.
    b. Wind speed less than 10 mph.
    c. Zero cloudiness.
   
