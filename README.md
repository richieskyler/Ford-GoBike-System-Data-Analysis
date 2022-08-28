# (Ford GoBike System Data)
## by (Richard Oloyede)


## Dataset

The Ford GoBike System Data contains 20 features ('duration_sec','start_time','end_time','start_station_id','start_station_name','end_station_id','end_station_name','bike_id','user_type','member_birth_year', 'member_gender','bike_share_for_all_trip') and other with 183,412 datapoint for individauls in a bike-sharing system covering the greater San Francisco Bay area.for the month of Feburary 2019


## Summary of Findings
There is close no(zero) correlation between the Bike ride duration and other quantitative variables where further analysis were done with qualitative variable to check for relationship

The boxplot showing the relationship between duration_sec and user_type indicates that most high duration are done mostly by the user_type customer which was futher approved by a multivariate regplot showing most long duriation rides are by customers in the age range 20's-30's

Also longer bike ride duration usually start on weekdays i.e friday,saturday and sunday


Moreover outside of the main variables there  appears to be a very strong correlation between hour_start_time and hour_end_time i.e (the relationship between the time an individual start and end a bike ride is positively correlated)
Also strong positive correlation between the day_start_time and day_end_time i.e it can be predicted the day an individual will end a ride based on the day the individual starts the ride

## Key Insights for Presentation

For my presentation i focused on when most the trips are taken in terms of time of the day and time of the week. Also try in understanding the some charateristics the influences longer bike ride.
I started by creating a barchart on the hours of the day and days of the week to indentify when most trips are taken. 
Also for understanding the charateristics that affects Bike Ride duration, a correlation plot was plotted using Heatmap to know the perecentage of correlation with other numerical variables . further analysis was done using bivariate plot and multivariate plot to further understand the influences of categorical variables on Bike Ride Duration. 