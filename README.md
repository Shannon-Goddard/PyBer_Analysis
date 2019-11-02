# PyBer_Analysis

## Project Overview
As we build a variety of charts, we will leverage our knowledge of Python arrays and turples, and learn how to apply Pandas methods, functions, and conditional expresion, as well as perform mathematical calculations on Series and DataFrames.

By the end of this module, we will be able to:
- Create line, bar, scatter, bubble, pie, and box-and-whiskers plots using Matplotlib.
- Add and modify features of Matplotlib charts.
- Add error bars to line and bar charts.
- Determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Resources
- Data Source: city_data.csv, ride_data.csv 
- Software: Anaconda 4.7.12, PythonData, Jupyter Notebook, Pandas, SciPy, and NumPy

## Summary
![Fig1](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig1.png)

![Fig2](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig2.png)

![Fig3](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig3.png)

![Fig4](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig4.png)

![Fig5](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig5.png)

![Fig6](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig6.png)

![Fig7](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig7.png)

## Challenge Overview
We've been asked by our CEO to create an overall snapshot of the ride-sharing data. In addition to our scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

### Objectives:
- Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
- Use Pandas methods and attributes on a DataFrame or Series.
- Create a newDataFrame from multiple groupby() Series.
- Format columns of a DataFrame.
- Create a multiple-line graph.
- Annotate and apply styling to the chart.

## Challenge Summary
Create a summary DataFrame that showcases the following:

  -Total Rides
  -Total Drivers
  -Total Fares
  -Average Fare per Ride
  -Average Fare per Driver

### Summary DataFrame <br/>
|                | Total Rides    | Total Drivers  | Total Fares    | Average Fare per Ride| Average Fare per Driver |  
| -------------- |:--------------:|:--------------:|:--------------:|:--------------:|---------------:|
| Rural          | 125            | 78             | $4,327.93      | $34.62         | $55.49         | 
| Suburban       | 625            | 490            | $19,356.33     | $30.97         | $39.50         | 
| Urban          | 1,625          | 2,405          | $39,854.38     | $24.53         | $16.57         | 

The summary DataFrame shows that the Rural Average Fare per Ride and Average Fare per Driver is significantly higher than that of the Suburban and Urban city types. This can be correlated to the Total Rides and Total Drivers being significantly less than that of the Suburban and Urban city types.

Create a Multiple-Line Plot for the Sum of the Fares for Each City Type
![Fig8](https://github.com/Shannon-Goddard/PyBer_Analysis/blob/master/analysis/Fig8.png)
