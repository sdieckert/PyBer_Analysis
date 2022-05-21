# PyBer_Analysis

## Project Overview
V. Isualize asked for a new analysis on the ride-sharing data by city type. In order to complete the assignment, Pandas and Matplotlib will be utilized to create a summary DataFram of the ride-sharing data by city type and a multiple-line graph that shows the total weekly fares for each city type. 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.2, Jupyter Notebook

## Challenge Overview
Challenge consists of two technical analysis deliverables and a written report to present your results. Submit the following:

### Deliverable 1: A ride-sharing summary DataFrame by city type
-The total number of rides for each city type is retrieved. 
-The total number of drivers for each city type is retrieved. 
​-The sum of the fares for each city type is retrieved.
​-The average fare per ride for each city type is calculated.
-The average fare per driver for each city type is calculated.
-A PyBer summary DataFrame is created.
-The PyBer summary DataFrame is formatted as shown in the example. 

### Deliverable 2: A multiple-line chart of total fares for each city type
-A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. 
-A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
-A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28.
-A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. 
-An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 

## Results

### Deliverable 1:

![Summary_Challenge](https://user-images.githubusercontent.com/87085239/169617047-0b6fe104-f191-4115-95bf-3d0e5122b003.png)


Reviewing the summary data by city type, we can see that as the city type moves from Rural to Urban, the number of rides increases as well as total drivers. This can be related to the higher frequency of riders requesting rides in Urban areas so therefore there's more opprotunity to provide that service. The average fare per ride and average fare per driver is higher in Rural, probably due to the distance involved being greater in rural areas. The greatest amount of rides being serviced and revenue is in the Urban areas. 

### Deliverable 2:

![FigChallenge](https://user-images.githubusercontent.com/87085239/169617071-c2cfa1d2-a37e-4e5b-bf28-cc78f4cf8085.png)


Reviewing our line graph where city type plotted against weeks from January to April, Rural and Suburban follows the same general pattern of rides by week, with similar spikes and drops during the months. Urban has more spikes, particulary from the middle of February to end of April. This could be due to seasonal tourism centered around spring break cycles which is why you may not see spikes in the Suburan and Rural areas. Also, the time frame we are reviewing, is during winter months going into spring, so increase in rides and total fares could be dependent on weather. 

## Summary
- I would recommend bringing in temperate and weather data to see if there's a relation between the hotter and colder days and increase in demand for rides. It would allow the company to increase their number of driver to meet demand. More time needs to be brought into the analysis to get an overall picture for an entire year.

- I would also recommend surveying the types of vehicles the drivers use as well as bringing in data on the total distance for each ride in order to determine if rural drivers are less likey to accept rides due to wear on their vehicle. If there is a relation, there may be an incentive or cost of wear for rurul drivers in order to accept longer distance rides. 

- Looking at Suburban, it appears there may be an opprotunity to increase the total revenue by increasing the number of drivers. With only 20% of the drivers compared to Urban, it brings in about 49% of the revenue compared to Urban. If advertising was targeted toward suburan riders going into the city, Suburan could be compariable or higher than Urban with not as many drivers needed. 
