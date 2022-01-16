Data set is available at : http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset. Date Donated -2013-12-20





This dataset was provided by Hadi Fanaee Tork using data from **Capital Bikeshare.**
Bike sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become automatic. Through these systems, users are able to easily rent a bike from a particular position and return back at another position. 
Currently, there are about over 500 bike-sharing programs around the world which are composed of over 500000 bicycles. 
Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.






## **Data Description:**

datetime - hourly date + timestamp

season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 

holiday - whether the day is considered a holiday

workingday - whether the day is neither a weekend nor holiday

weather -

1: Clear, Few clouds, Partly cloudy, Partly cloudy

2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 

temp - temperature in Celsius

atemp - "feels like" temperature in Celsius

humidity - relative humidity

windspeed - wind speed

casual - number of non-registered user rentals initiated

registered - number of registered user rentals initiated

count - number of total rentals






## **Goal of our project:**

The training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. We have to predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.


## **Random Forest** performed optimally when compared the scores of all the models, with the least RMSE (~0.39) & best R2 (~0.91).
