# Data 602 Linear Regression Model HW1
 Course project on Linear Regression Modeling.
 
 ## Overview
 - Data on two years of bike-share metrics including: weather, registered and casual riders, and dates.
 - Can this data help predict the demand for bikes?
 - Contents
   -[602_HW1_Bike.pynb : EDA and first looks](https://github.com/marcelthebridge/Data-602-Linear-Regression-Model-HW1/blob/master/602_HW1_Bike.ipynb)
   -[602_HW1_Report.ipynb : Streamlined report](https://github.com/marcelthebridge/Data-602-Linear-Regression-Model-HW1/blob/master/602_HW1_Report.ipynb)
   -[Bikeshare.csv : Dataset](https://github.com/marcelthebridge/Data-602-Linear-Regression-Model-HW1/blob/master/Bikeshare.csv)
   -[README.md : Readme file](https://github.com/marcelthebridge/Data-602-Linear-Regression-Model-HW1/blob/master/README.md)
 
 
 ## Goals
 - To create a model capable of predicting bike needs over a yearly forecast 
 
 ## Data
 - Data is from DC BikeShare, and originially retrieved from [Kaggle](https://www.kaggle.com/poornimakeshavaiah/bikesharing)
 * Features:
   * Instant | Index starting at 1
   * dteday | Date of ride
   * season | Season
   * year | Year
   * mnth | Month
   * holiday | Holiday (binary)
   * weekday | Weekday (0-7)
   * workingday | Working day (binary)
   * weathersit | Weather Situation (1-3)
   * temp | Temperature (celsius)
   * atemp | Ambient Temperature (celsius)
   * hum | Humidty (%)
   * windspeed | Windspeed
   * casual | Casual Riders
   * registered | Regostered Riders
   * cnt  | Total Rider Count
