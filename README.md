# sqlalchemy-challenge
## Observasion

##  Part 1: I analyse explore climate data

In this section, i used  Python and SQLAlchemy 

by using files (climate_starter.ipynb and hawaii.sqlite) to completed climate analysis and data exploration.

by using the SQLAlchemy create_engine() function to connect to  SQLite database.

by using the SQLAlchemy automap_base() function to reflect tables into classes, and then save references to the classes named station and measurement.

Link Python to the database by creating a SQLAlchemy session.

# Precipitation Analysis

Analyse the most recent date in the dataset.

Using that date, analysed previous 12 months of precipitation data by querying the previous 12 months of data.

Sort the DataFrame values by "date".

Plot the results by using the DataFrame plot method.

# Station Analysis

Design a query to calculate the total number of stations in the dataset and 
the most-active stations (that is, the stations that have the most rows). 

-- List the stations and observation counts in descending order.

--  which station id has the greatest number of observations?
answer:  by using station id  data set observed greatest number. that is showed in Graph.

-- and also find descending order of obesrvations


## part-2: Design Climate APP.

designed a Flask API based on the queries that you just developed, by use Flask to created routes as follows:

1. / (design home page)

2. /api/v1.0/precipitation

3. /api/v1.0/stations

4. /api/v1.0/tobs

5. /api/v1.0/<start>  and  /api/v1.0/<start>/<end>

and return JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.

and  a specified start, calculate TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date.

For a specified start date and end date, calculate TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.

image.png






