# MotoGP_Data_2005_2017.csv

Ankur Vishwakarma  
Metis SF Winter 2018  



**Summary of Data**

This file contains the following data points for racing sessions only between 2005 and 2017 in all 3 racing classes. 

* **Year:** `int` value of racing season.
* **TRK:** three character `str` abbreviation of track.
* **Track:** full name of the race in `str` format.
* **Category:** class of racing, whether it's MotoGP, Moto2, 125cc, etc. as a `str`.
* **Session:** `str` if the race was a RAC (race) or RAC2 (race2) session of the day. 
* **Date:** pandas readable `datetime` (date only) of the race.
* **Track_Condition:** `str` format racetrack conditions, whether dry, wet, or dry-wet.
* **Track_Temp:** `float` value of track ground temperature in celsius (C).
* **Air_Temp:** `float` value of air temperature in celsius (C).
* **Humidity:** `float` value of local humidity between 0 (0%) and 1 (100%). 
* **Position:** finish order of the particular rider. Denotes 'crash' if rider crashed before finishing. 
* **Points:** `float` value of points earned by rider during this race session.
* **Rider_Number:** rider's racing number.
* **Nationality:** rider's nationality as a `str`.
* **Team_Name:** team that the rider belongs to during this race session.
* **Bike:** manufacturer of the motorcycle ridden by rider during this race session.
* **Avg_Speed:** average speed of the rider during this race session in km/h. 
* **Time:** `str` value of the finishing time for the winning rider. Riders finishing 2nd or worse have the added time value. Riders who crash have the number of full completed laps indicated.
* **Finish_Time:** pandas `timedelta` value obtained from the **Time** column. This is each rider's total time to finish the race. Crashed riders are ignored. 
* **GP:** concatenated track abbreviation and name used to pull in track data. 
* **track_length_km:** total track length in kilometers (km).
* **l_corners:** number of left corners.
* **r_corners:** number of right corners.
* **width_m:** average width of racetrack in meters (m).
* **straight_m:** length of track's longest straight in meters (m).
* **GP_avg_speed:** average speed of MotoGP motorcycles around the track in kilometers per hour (km/h) if available.
* **gp_dist:** distance raced by MotoGP class bikes in kilometers (km).
* **m2_dist:** distance raced by Moto2 class bikes in kilometers (km).
* **m3_dist:** distance raced by Moto3 class bikes in kilometers (km).

