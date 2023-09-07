## Hypothesis Testing

## Project Title : 
Understand the factors affecting the demand for these shared electric cycles in India - Hypothesis Testing

## Project Description :

One of the India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, it provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

operating stations are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

## Business Problem :

One of the India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. it has recently suffered considerable dips in its revenues. We have a data to analyze why considerable dips in its revenues.

The company wants to know:
- Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
- How well those variables describe the electric cycle demands
- Revenue generations insights
- Predict the demand of shared electric cycles in perticular seasons/weather so that supply will be in reach the demand

## Data Preview

- datetime: datetime
- season: season (1: spring, 2: summer, 3: fall, 4: winter)
- holiday: whether day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
- workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
- weather:
  1. Clear, Few clouds, partly cloudy, partly cloudy
  2. Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  3. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  4. Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp: temperature in Celsius
- atemp: feeling temperature in Celsius
- humidity: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- count: count of total rental bikes including both casual and registered

## Tools and Language : 

Jupyter Notebook (Python): Used for basic understanding like the structure of data (rows and columns), checking null values, handling missing values, etc.
Python Libraries: NumPy, Pandas, Matplotlib, Seaborn and scipy
