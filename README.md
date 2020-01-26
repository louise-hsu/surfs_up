# surfs_up

## Project Overview 
Performing data analytics and making a case for a shop (surf/ice creame/shake). It is important to check and make weather analysis of the island you would like to open the shop. 

1. Intro to SQLite, SQLAlchemy, and Flask
2. Precipitation Analysis
3. Weather Station Analysis
4. Flask
4. Build Climate App using Flask

This module has taught me the following:

1. Differentiate b/w SQLite and PostgreSQL
2. Use SQLAlchemy to connect to and query a SQLite database
3. Use statistics like minimum, maximum, and average to analyze data
4. Design a Flask application using data

## Documents

- .gitignore 
- readme.md - information
- app.py - Flask/routes
- climate_analysis.ipynb- the module and challenge
- flask_example - example of using flask
- hawaii.sqlite - the sqlite data

## Summary
***Please note: all this information/code can be found in climate_analysis.ipynb

- The data precipitation from the last 12 months dates were found with the describe ():

      - count 2021
      - mean 0.18
      - std  0.48
      - min  0.00
      - 25%  0.00
      - 50%  0.02
      - 75%  0.13
      - max  6.70
      
- There are 9 different stations. 

      - The station with the most counts is USC00519281 with 2772 counts
      - The station with the least counts is USC00518838 with 511 counts.
      
- USC00519281 station data:

      - lowest temp: 54.0
      - highest temp: 85.0
      - average temp: 71.66
      
- USC0051281 has the highest number of temperature observations
      - The temperature of ~77 has highest frequency 
      
- The temperature summary statistics from June 1st, 2017 to June 30th, 2017 

      - min: 71
      - avg: 77.2
      - max: 83
      
# Module 9 Challenge 

## Challenge overview

1. Identify key statistical data in June across all stations and years using the decribe() function
2. Identify key statistical data in December across all stations and years using the describe() function
3. Share your findings in the Jupyter Notebook with a few sentences describing the key differences in weather between June and December and 2-3 recommendations for further analysis.

## Summary Challenge
***Please note the code/information can be found in the climate_analysis.ipynb

- The key statistical data in June across all stations and years 

     - Precipitation
      
          - count : 1574
          - mean : .136360
          - std : 0.335731
          - min : 0.00
          - 25% : 0.00
          - 50% : 0.02
          - 75% : 0.12
          - max : 4.43
          
     - Temperature 
      
          - count : 1700
          - mean : 74.944118
          - std : 3.257417
          - min : 64.0
          - 25% : 73.0
          - 50% : 75.0
          - 75% : 77.0
          - max : 85.0
- The key statistical data in December across all stations and years

     - Precipitation
      
          - count : 1405
          - mean : 0.216819
          - std : 0.541399
          - min : 0.00
          - 25% : 0.00
          - 50% : 0.03
          - 75% : 0.15
          - max : 6.42
          
     - Temperature
      
          - count : 1517
          - mean : 71.041529
          - std : 3.745920
          - min : 56.0
          - 25% : 69.0
          - 50% : 71.0
          - 75% : 74.0
          - max : 83.0
          
## Challenge Analysis (Can be found in the Jupyter notebook)

The differences in weather between June and December:

1. June's average temperature was ~75 and December's average temperature was ~71, which shows that in the temperature in June is warmer compared to the temperature in December.

2. June's average precipitation is .14 and December's average precipitation is .22. The data shows that it precipitates more in December compared to June


## Recommendations (Can be found in the Jupyter notebook)

1. Identify the location of the station and the weather description based on station. This will allow to further identify and pin point a better location with better weather. Weather can differ based on location, on different parts of an island. 

2. If we identify the location of the station and weather description based on station, we will also need to look at number of temperature observation per station, so we do not get skewed results. 

3. Even though the data contains temperature, it would be beneficial to find the weather forecast (sunny, partially cloudy, etc.). The sunnier or "nicer day" would attract more people to go out and maybe increase the possibility to go to the ice cream shop or surf.
