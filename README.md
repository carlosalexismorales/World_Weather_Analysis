# World_Weather_Analysis

## Project Overview

This analysis looks at PlanMyTrip, travel company that specializes in using technology and internet related services in the hotel and lodging industry. This assignment adds in additional information and insight for consumers to look at when planning their trips such as different weather patterns around the globe.

This project consists of three technical analyses that will provide a more informative and helpful experience for consumers:

1. Retrieving weather data, including the weather description
2. Creating a customer travel destinations map
3. Creating a travel itinerary map.

## Resources

- Data Source:
  - WeatherPy_vacation.csv
  - WeatherPy_database.csv

- Software:
  - Python Python 3.10.5
  - Conda 4.13.0
  - Jupyter Notebook 6.4.11
  - Pandas 1.4.2
  - citipy
  - Google Maps and Places API
  - Google Maps Directions API

## Results

### Retrieving weather data

This folder takes the information gained in the weather database and uses Google Maps API to plot different travel destinations with a hotel at each location. In the image below, the database is created useing the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).

<img width="991" alt="Screen Shot 2022-07-06 at 9 56 32 PM" src="https://user-images.githubusercontent.com/102444078/177694463-036703ea-5170-472d-8e03-b4bff1798307.png">



### Creating a customer travel destinations map

This folder takes Jupyter's gmaps plugin, user's weather preference inputs and requests to the [Google Maps and Places API]
In the image below, a map is  shown with the locations of all the places in the database that have an daily maximum temperature between 75 and 90 degrees farinheit - 3 are selected. 

<img width="1332" alt="Screen Shot 2022-07-06 at 9 58 14 PM" src="https://user-images.githubusercontent.com/102444078/177694664-4383b14a-2136-47f6-9442-92822f4528b0.png">

### Creating a travel itinerary map

This folder takes the search information from the search folder and uses Google Maps directions API to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Northern California that features Ukiah, Carson City, Laguna, and Half Moon Bay.
