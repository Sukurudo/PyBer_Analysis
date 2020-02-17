# Challenge
You’ve been asked by your CEO to create an overall snapshot of the ride-sharing data. In addition to your scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

# Objectives
The goals for this challenge are for you to:

- Use Pandas functions like groupby, pivot, resample, and reset_index on a DataFrame.
- Use Pandas methods and attributes on a DataFrame or Series.
- Create a new DataFrame from multiple groupby() Series.
- Format columns of a DataFrame.
- Create a multiple-line graph.
- Annotate and apply styling to the chart.

## Resources
- Data Source: city_data.csv & ride_data.csv
- Software: Python 3.6.1, Jupyter Notebook

## Create a Summary DataFrame

Summary of Data
| | Total Rides |	Total Drivers |	Total Fares |	Average Fare per Ride |	Average Fare per Driver |
|---|---|---|---|---|---|
| Rural |	125 |	78 |	$4,327.93 |	$34.62 |	$55.49 |
| Suburban |	625 |	490 |	$19,356.33 |	$30.97 |	$39.50 |
| Urban |	1,625 |	2,405 |	$39,854.38 |	$24.53 |	$16.57 |

This information shows that as we move from Rural to Urban the demand for rides increases. Urban areas account for the majority of the rides and a large portion of the fares. Even with the lowest of the average fare price, Urban areas account for 63% of the total fares. Rural prices are higher due to the fact that demand is lower, so there are less drivers. With fewer drivers around the price goes up.

## Fares by City Type (Jan 1, 2019 - Apr 28, 2019)

![Table1](/analysis/challenge5.png)

This table shows the breakdown of fares collected by city type for the months between January 1, 2019 and April 28, 2019. On average, the rises and drops are all similar across all city types. There is a slow rise in January, a sharp peak at the end of February, then a drop in March.  There is a little bit of a rise in April. This chart also shows that there is a strong separation between the three city types. The Urban areas collect higher fares across the entire period, staying between $1,500 and $2,500. Suburban areas stay between $500 and $1,500, while Rural areas stay between 0 and $500. This shows that demand is all areas are significantly different from each-other.

In summary, this chart confirms the summary of data chart earlier. because of higher demand, there are more rides and more fares generated in Urban areas. The more people in an area, the higher revenue that will be generated. As there is more supply (drivers) in the Urban areas, the price goes down and the demand goes up- resulting in higher profits.
