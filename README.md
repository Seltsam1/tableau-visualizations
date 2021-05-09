# tableau-visualizations
Charts and maps of NYC City Bike

## Getting Started

The resulting Tableau file contains charts and maps from the New York City Bike Program (data available at https://www.citibikenyc.com/system-data)

Download the files to get started. The jupyter notebook shows data integrity and cleaning steps (done in python using pandas). Details on the Tableau file are included below

## Features

- Cleaning/cleaning-steps.ipynb
  - Examines the April 2021 csv file for missing data and confirms datatypes
  - Appends 6 months of data (from Nov 2020 to April 2021) and exports as a csv file

- tableau.twb
  - File created using Tableau Desktop 2021.1
  - Contains 8 sheets, placed into two dashboards
    - Maps of start and end stations include popularity (counts), zip code data, and map layer for household income
    - Two tables of the top 10 start and end stations with names and counts
    - Two line charts of trip duration, one by birth year and the other by age
    - Bar charts of count and trip duration by gender (men and women)
    - Timeseries line chart by gender (men and women)
  - Story contains both dashboards
    - First shows station details with analytic writeup
    - Second shows demographic details with analytic writeup 

## Licensing by:

The code in this project is licensed under MIT license.
