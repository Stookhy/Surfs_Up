# Surfs_Up

## Overview of the Statistical Analysis

1.	Using Jupyter notebook to generate codes.
2.	Using SQLite to provide a database engine without requiring a server. 
3.	Matplotlib dependencies to create a graph the results.
4.	Use SQLAlchemy to connect to and query an SQLite database. 
5.	Key concepts in statistics to create a table with count, mean, minimum, maximum
6.	Incorporate Flask into data analysis


## Purpose

    The purpose is to determine temperature trends before opening the surf shop. Specifically, this requires puling temperature data for June and December in Oahu to regulate if the shops business is sustainable year-round. 


## Results

*   The average temperature in June (74.94 degrees) is higher than the average temperature in December (71.04 degrees)
*   There is a higher temperature variation in December (std 3.74) compared to June (3.25)
*   The most frequent temperature in June (around 74 degrees) is higher than the most frequent December temperature (around 71 degrees)
*   The minimum temperature in December (56 degrees) is significantly less than the minimum temperature in June (64 degrees)

JUNE

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/June_Temp.png?raw=true)

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/June_Temps_Chart.png?raw=true)

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/June_Temps_Plot.png?raw=true)


DECEMBER

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/December_Temp.png?raw=true)

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/December_Temps_Chart.png?raw=true)

![This is an image](https://github.com/Stookhy/Surfs_Up/blob/main/Resources/December_Temps_Plot.png?raw=true)


## Summary

*   Overall, given the higher more frequent temperatures in June and lower more frequent temperatures in December, is it not sustainable to open the surf and ice cream shop year-round.
*   Two additional queries that would be beneficial in getting more weather data for June and December are:
    *   Running a query to filter the date column according to a minimum temperature. This will help determine how many days within the 2 months are viable days to open the surf and ice cream shop
    *   Running a query to remove outliers. This will ensure that the statistics, particularly the mean, are not skewed inappropriately. 
    

