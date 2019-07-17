# Risk-Factor-Identification-using-Truck-Fleet-Sensor-Data

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

- This usecase is to analyse various parameter of a truck fleet.
- Each truck has been equipped to log location and event data.
- These events are streamed back to a datacenter where we will
be processing the data.
- The company wants to use this data to better understand risk.

# Goal of the Project
* To get familiar with end to end implantation of a big data project using various tools in Hadoop ecosystem.

# Data
* Collected geo-location and truck data has been provided.
* Truck data is small and can be stored in RDBMS – to be imported from sqoop.
* Geo-location data will be stored on HDFS

# Architecture
![alt-text](https://2xbbhjxc6wk3v21p62t8n4d4-wpengine.netdna-ssl.com/wp-content/uploads/2014/05/syncsort2.png)

# Steps

* Load the captured sensor data into Hadoop (HDFS)
* Load truck data from RDBMS to HDFS/Hive
* Run Hive, Pig scripts that compute truck mileage and driver risk
factor.
* Access the refined sensor data with Microsoft Excel
* Visualize the sensor data using Excel Power View / Pivot Table /Graphs.

# Loading Data into Hive
![load-data](https://user-images.githubusercontent.com/22028693/48166775-9dd9f680-e2b7-11e8-96b0-96549a2c2832.png)

# Analysing Data

The business objective is to better understand the risk the company is under from fatigue of drivers, over-used trucks, and the impact of various trucking events on risk.

![load-data-2](https://user-images.githubusercontent.com/22028693/48166831-d5e13980-e2b7-11e8-9b48-656df0d9a34f.png)


