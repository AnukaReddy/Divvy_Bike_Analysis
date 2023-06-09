# Divvy Bike Share Data 
### Spatial analysis of Divvy Bike Share Data to identify areas with high demand for bike infrastructure. 
Data: Divvy Bike Trips, Chiicago, IL, August, 2019
Anuka Reddy, Commmand Line GIS, Fall 2022  
Edward J. Bloustein School of Planning and Public Policy, Rutgers University

The datasets was obtained from Divvy Bikes (https://divvybikes.com/system-data) in for the year 2019, in August to analyze pre-covid demand for bike share systems in order to improve biking infrastructure at different locations. 

About Divvy Bikes - Divvy is a bike share system that provides locals and visitors of Chicago, with access to a fleet of well-designed bikes that are stationed all over the area. These bikes can be unlocked from one station and returned to another, making it easy to get around without worrying about parking or traffic. And these bikes and stations are accessible 24/7, all year long.

Lyft Bikes and Scooters, LLC (“Bikeshare”) operates the City of Chicago’s (“City”) Divvy bicycle sharing service. Bikeshare and the City are committed to supporting bicycling as an alternative transportation option. As part of that commitment, the City permits Bikeshare to make certain Divvy system data owned by the City (“Data”) available to the public, and updated every month. 

The data for this analysis was downloaded in the 'csv' format and used as it is. 
The final index layer was developed using multiple geoprocessing tools in Geopandas.
This project includes two interactive and static tract-level maps showing bike stations and and accessible transit stations in proximity to these bike stations, along with Maps that project the percentage of population who do not have vehicle ownerships and are dependent on public transit. 

### Static Map 1
![No_cars](https://user-images.githubusercontent.com/132031769/235501231-8229d36a-089a-475e-b807-a173abfc3a60.png)

### Static Map 2
![Public Transit](https://user-images.githubusercontent.com/132031769/235051091-2bc2f08f-f846-41a7-91b1-68e218f08d21.png)

### Interactive Map  - Divvy Bike Stations
<iframe src="BikeStation_Map.html" height="800" width="95%"></iframe>

### Interactive Map  - Bus Stops in Proximity to the Divvy Bike Stations
<iframe src="Bus_Stops.html" height="800" width="95%"></iframe>


