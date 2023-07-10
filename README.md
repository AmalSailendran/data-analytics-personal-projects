# data-analytics-personal-projects
A repository of the various personal data analytics projects I had worked on.

# U.S. International Air Traffic Data Analysis

![Airplane Image](airplane_image.jpg) <!-- Replace with an appropriate image -->

This project involves the analysis of U.S. International Air Passenger and Freight Statistics data. The data is sourced from the U.S. Department of Transportation (USDOT) as part of the T-100 program, which collects traffic reports from U.S. and international airlines operating to and from U.S. airports.

## Dataset Overview

The dataset consists of two main datasets:

1. Departures: Data on all flights between U.S. gateways and non-U.S. gateways, providing information on specific airlines for airport pairs. The data includes columns such as Scheduled flights, Charter flights, and Total flights.

2. Passengers: Data on the total number of passengers for each month and year between a pair of airports, based on specific airlines.

Please note that the U.S. International Air Passenger and Freight data are confidential for six months and are released after that period. Hence, the provided quarterly reports and year-to-date/calendar year raw data files will lag by two quarters.

## Questions Answered

The analysis of the U.S. International Air Traffic Data aims to answer the following questions:

1. What is the overall trend in the total number of flights over the years?
2. Which year had the highest total number of flights? Was there any specific reason for this increase?
3. What are the top 10 busiest airports based on the total number of flights?
4. Is there a difference in the number of flights between domestic and foreign carriers?
5. Which airline had the highest number of flights? Have there been any shifts in the dominance of airlines over the years?

## Additional Information

For a more detailed analysis and to access the dataset, please refer to the Kaggle link provided below:

[Link to Kaggle Dataset](https://www.kaggle.com/datasets/parulpandey/us-international-air-traffic-data?resource=download&select=International_Report_Passengers.csv)

## Data Analysis Code

The Python code used for the data analysis can be found in the accompanying Jupyter Notebook [here](analysis.ipynb).



