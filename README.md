## Project1: Exploring Climate Data of Singapore for Tourism purpose

### Problem Statement

Singapore's tropical region leads to the country being affected by multiple rainfalls in a year. As an analyst for the tourism industry, my analysis of the climate data will help us understand the trends and gain insights into Singapore's climate over 40 years. Moreover, the analysis will also help understand factors that cause rainfall. Ultimately, these insights will transform into recommendations for the tourism industry in identifying the periods that are less likely to be affected by adverse climate and announced publicly to visitors worldwide.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|total_rainfall|float|rainfall-monthly-total|Total rainfall in mm| 
|no_of_rainy_days|int|rainfall-monthly-number-of-rain-days|Number of rain days in days|
|mean_rh|float|RelativeHumidityMonthlyMean|Monthly mean of relative humidity in celsius|
|mean_sunshine_hrs|float|SunshineDurationMonthlyMeanDailyDuration|monthly mean of daily sunshine duration in celsius|
|wet_bulb_temperature|float|WetBulbTemperatureHourly|Wet bulb temperature, hourly in celsius|
|mean_temp|float|SurfaceAirTemperatureMonthlyMean|Monthly temperature mean in celsius|
|total_international_visitor_arrivals|int|TotalVisitorInternationalArrivalsMonthly|Number of international arrival visitors in thousands|

### Analysis

- Rainfall amount in Singapore is at the lowest amount during February. June and September are also the months that have comparatively less rainfall. 
- Factors that contribute to rainfall are:
    1) sunshine hours, where less duration of sunshine means more rain
    2) relative humidity, where higher humidity means a higher amount of rainfall
    3) mean temperature, where lower temperature likely to cause more rainfall
    4) number of rainy days, where more rainy days mean a higher amount of rainfall
- More visitors visit Singapore when rainfall is low (0-300 mm). This is incongruent with the chart that shows that most visitors come to Singapore during July and August which is the summer break period and the rainfall are low. 

### Recommendation

- Promote international visitors to visit Singapore during February when the amount of rainfall and the number of rainy days are the lowest. The number of visitors is also low compared to July and August when the number of visitors is the highest (peak season). Other optimal months to visit are June and September because the rainfall amount is low, less rainy days, and low amount of visitors. 
