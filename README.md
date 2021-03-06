# wunder-weather

Script to scrape weather data from wunderground.com for a given city and year range. Input city should be wunderground.com's id for it (ex: CYUL for Montreal, KNYC for NYC). Outputs to a csv file in the same directory called city_startyear_endyear_weather.csv.

This is useful because using the API for free limits you to 500 calls/day, so it would take about a month to scrape all of their (reliable) data, which I think is from 1965 onwards. This takes about 6 hours. 

Made with my love for my little brother who is attempting to incorporate weather into a financial model, as if that's never been done before. 

------

```
Usage: python wunder.py city start_year end_year
```

------
What does it get? The actual, average, and record (when applicable) for: 
+ Mean Temperature
+ Max Temperature
+ Min Temperature
+ Heating Degree Days
+ Month to date heating degree days
+ Since 1 July heating degree days
+ Cooling Degree Days
+ Month to date cooling degree days
+ Year to date cooling degree days
+ Dew Point
+ Average Humidity
+ Maximum Humidity
+ Minimum Humidity 
+ Precipitation
+ Month to date precipitation
+ Year to date precipitation
+ Snow
+ Month to date snowfall
+ Since 1 July snowfall
+ Snow Depth
+ Sea Level Pressure
+ Wind Speed
+ Max Wind Speed
+ Max Gust Speed
+ Visibility
+ Events
