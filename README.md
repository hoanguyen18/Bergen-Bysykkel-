# Bergen-Bysykkel-
- Scraping API data from Bergen Bysykkel (https://bergenbysykkel.no)- a company that rents out bicycles in Bergen, Norway. They release data through an open API.
- Read the .json-file. Write a pipeline that transforms it into a data frame with the same columns/format as the .csv-file.(json-format)
- Data clean, wrangling and validation to create a datset with following variables: datetime, station_ID, start_hour, n_rides, weekday...
- Estimate a linear regression model for each of the stations, using factors for weekdays and hour of day as explanatory variables and n_rides as the response variable. 
- Predict the number of rides for each hour of day, weekday and station using these regression models. Collect the predictions in a data structure, together with the station ID.
- Create a set of plots showing the predicted number of bicycle rides throughout an entire week. Place predicted volume on the y-axis and the hour of day on the x-axis. Make one plot per day of week. Use different colors for each station, and format the plots as appropriate.
- Write a function to take as arguments the date and the hour, return a plot (ggmap) of the city with the information about traffic volume
Package usage: The json-format, data wrangling and joining of different data sources (tidyverse, dplyr), working with dates (lubridate), making maps (ggmap), fitting many models (purrr).
