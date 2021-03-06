# covid_19_jhu_data_web_scrap_and_cleaning
This repository contains data and code used to get and clean data from https://github.com/CSSEGISandData/COVID-19 and https://www.worldometers.info/coronavirus/

## JHU data
* https://github.com/CSSEGISandData/COVID-19 contains the data that supports JHU's dashboard at https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

## worldometer data
* The data is scrapped from https://www.worldometers.info/coronavirus/
* According to worldometer 
> "For the COVID-19 data, we collect data from official reports, directly from Government's communication channels or indirectly, through local media sources when deemed reliable. We provide the source of each data update in the "Latest Updates" (News) section. Timely updates are made possible thanks to the participation of users around the world and to the dedication of a team of analysts and researchers who validate data from an ever-growing list of over 5,000 sources." - https://www.worldometers.info/about/

## Files

* *data_cleaning.ipynb* - Notebook used to get, clean and save data  
* *flurish_script.ipynb* - Notebook used to format data to create flurish running bar chart  
  
* *covid_19_clean_complete.csv* - Country wise day to day cases dataset  
* *usa_county_wise.csv* - US county day to day cases dataset  

* *time_series_covid19_confirmed_global.ipynb* - Has day to day global confirmed cases data  
* *time_series_covid19_deaths_global.ipynb* - Has day to day global deaths data  
* *time_series_covid19_recovered_global.ipynb* - Has day to day global recovered data  
  
* *time_series_covid19_confirmed_US.ipynb* - Has day to day US confirmed cases data  
* *time_series_covid19_deaths_US.ipynb* - Has day to day US deaths data  
