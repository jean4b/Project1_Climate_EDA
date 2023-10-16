## Project1: Exploring Climate Data of Singapore for Tourism purpose

### Problem Statement

Singapore situated in tropical region leads to the country being affected by multiple rainfalls in a year. As an analyst for the tourism industry, my analysis on the climate data will help see the trends and gain insights of Singapore's climate throughout the period of 40 years. Moreover, the analysis will also help understand factors that cause rainfall. Ultimately, these insights will transform into recommendations for the tourism industry in identifying the periods that are less likely to be affected by adverse climate and announce publicly to visitors worldwide.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|total_rainfall|float|rainfall-monthly-total|Total rainfall in mm| 
|no_of_rainy_days|int|rainfall-monthly-number-of-rain-days|Number of rain days in each month|
|mean_rh|float|RelativeHumidityMonthlyMean|Monthly mean of relative humidity
|mean_sunshine_hrs|float|SunshineDurationMonthlyMeanDailyDuration|monthly mean of daily sunshine duration
|temp_mean_daily_min|float|SurfaceAirTemperatureMonthlyMeanDailyMinimum| average daily minimum temperature 
|wet_bulb_temperature|float|WetBulbTemperatureHourly|Wet bulb temperature, hourly in celsius|
|mean_temp|float|SurfaceAirTemperatureMonthlyMean|Monthly temperature mean
|total_international_visitor_arrivals|int|TotalVisitorInternationalArrivalsMonthly|Number of international arrival visitors

### Analysis

-  Rainfall amount in Singapore is at the lowest amount during June. April, July, August, and October are all the months that comparativey have less rainfalls. 
- Factors that contribute to rainfall are:
    1) sunshine hours, where less duration of sunshine means more rain
    2) relative humidity, where higher humidity means higher amount of rainfall
    3) mean temperature, where lower temperature likely to cause more rainfall
    4) number of rainy days, where more rainy days means higher amount of rainfall
- More visitors visit Singapore when amount of rainfall is low (0-300). This is incongruent with the chart that shows that most visitors come to Singapore during July and August which is the summer break period and the rainfall are low. 

### Recommendation

- Promote the international visitors to visit Singapore during June where the amount of rainfall is the lowest and the number of visitors is lower comparing to July and August where the number of visitors are the highest (peak season), although the amount of rainfall is also low. Other optimal months to visit are April and October, because the rainfall amount is low and not much visitors. 
