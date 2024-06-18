Introduction
===============

PRISM provides precipitation data based on location, as far back as 1981.
This dataset was generated with the parameters:
* Location:  Lat: 35.5515   Lon: -97.4072   Elev: 1171ft
* Climate variables: ppt,tmin,tmean,tmax,tdmean,vpdmin,vpdmax
* Spatial resolution: 4km
* Period: 1981-01-01 - 2022-12-31
* Dataset: AN91d
* PRISM day definition: 24 hours ending at 1200 UTC on the day shown
* Grid Cell Interpolation: Off

This notebook is intended to demo the data analysis and data modelling process as a part of a portfolio. The ultimate goal is to be able to predict total precipitation (rain + melted snow). 
\
Feature Explanation
--------------------

| Name   | Description                                                                                                           | Units |
| ------ | --------------------------------------------------------------------------------------------------------------------- | ----- |
| ppt    | Total precipitation (rain+melted snow) for the day                                                                    | in    |
| tmin   | Minimum temperature for the day                                                                                       | F     |
| tmean  | Mean temperature for the day (tmax+tmin)/2                                                                            | F     |
| tmax   | Maximum temperature for the day                                                                                       | F     |
| tdmean | Mean dewpoint temperature (analogous to humidity and comfort)                                                         | F     |
| vpdmin | Minimum difference between the amount of vapor in the air, versus the total amount it can hold (relative to humidity) | hPa   |
| vpdmax | Maximum difference between the amount of vapor in the air, versus the total amount it can hold (relative to humidity) | hPa   |
