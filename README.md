# Exploring San Francisco Bike Rental Dataset
> by Deepak Nandipati

## Dataset
This dataset is of 2017 San Fransico and Bay area FordGoBike rentals. It consists of over 500,000 data points with variables such as the latitude, longitudes of data, timings of rentals, customers gender and user type. In my analysis, I would like to determine which group of riders are likely to have the longest rental duration and to also find out the timeperiod in which these riders are most active.

## Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## My Research Question
I want to determine which group of individuals are likely to have the longest rental duration and to find out what timespread these riders are most active in San Franciso.

## Key findings from analysis
BikeShare dataset provided great insights while analysis, with breakdown of data and using several wrangling techniques we got to answer our research question along with some interesting points. Below are the summarized notes from my analysis:
- Bikeshares only run from June - December and riders are most active during the fall and early season
- Age groups of 30-40 are most abundant in rentals, followed by 20-30 and 40-50; groups that directly pertain to working indivdiauls
- Age groups 60-70 rent the bikes for the longest time - assuming they are not of working class and use it for leisure purposes
- It was observed that the busiest time of day for rentals are during the busienss hours with heaviest rentals at 8:00 AM and 5:00 PM. Most of these users are subscribers to this service rather than customer type. 
- Following above point, weekdays were also the busiest for rentals but weekdays had marginally lower duration time than the weekends
- Weekend riders were mostly customers whom used it for leisure time and weekday customers tended to rent during the evening period
- Females are renting the bikes for longer period, and gender 'other' is followed with long durations

## Presentation of data
For the slide deck presentation, I isolated the main plots and data needed to answer my research question. The categories of interest where of the start_hour of rentals, counts of rentals during day of the week, age group comparisons, customer types and relations with duration of rental. Also, the distinction of data when introducing new variable: 'Gender'.

# Files Used
Exploration_Project_FordGoBike.ipynb| 2017-fordgobike-tripdata.csv| 
