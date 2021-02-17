# Ford Go Bike Data

>This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

## assesing summary
 * there are some unuseful columns :(end_time ,start_station_latitude ,start_station_longitude,end_station_latitude,end_station_longitude)
* some columns has null values : (start_station_id ,start_station_name, end_station_id ,end_station_name,member_birth_year, member_gender) 
* member_birth_year is float but it should be int
* start_station_id ,end_station_id is float but it better be int
* start_time is object but it should be datetime

## insights summary
* most members are males
* Thursday is the most day of the weak that members ride bikes, Saturday and Sunday are the least two days that members ride bikes the two days seems to be equal
* 90.5% of users are subscribers and only 9.5% are customers
* mean of ages is about 36 years old ,also the most frequent age is between 30 and 35 years old
* the relation between the members ages and ride duration is strongly negative, people above 70 years have the lowes hours duration (less than 2 hours) in the other hand the longest duration riders are between 20 and 50 years old
* customers spent more time using bike than subscribers
* most of males and womans whoes age betwwen 20 and 50 and have a long ride duration did not share the bike for all trip
* In all genders and ages people who did not share bike for all trip are more than who did
* males and females who shared bike for all trip are more than other who did
