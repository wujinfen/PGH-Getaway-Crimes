# Pittsburgh Getaway Crimes: Community Safety Analytics
This project uses police arrest data and vehicle speedhump data from the Western Pennsylvania Regional Data Center (WPRDC) to determine target neighborhoods in Allegheney County (The City of Pittsburgh) for attempted getaway crimes. 

The project was completed in Jupyter Notebook and created with Python utilizing the Pandas data analysis framework, NumPy for mathematical operations, and matplotlib for embedded plots. Additionally, we used the positionstack API to calculate and estimate incident-to-crime distances.

See <pgh-getaway-analytics.ipynb>

## Abstract

Along with regulating traffic and vehicle speeds, speedhumps serve as a deterrent for getaway crimes involving vehicles. My group coupled speedhump data with police arrest data to gauge criminal activity within each neighborhood. Additionally, we measured law enforcement presence in each neighborhood by analyzing the amount of arrests, the change in number of arrests over time, and the average distances between incident and arrest locations. Using these metrics, we found Squirrel Hill to be the safest neighborhood in Pittsburgh to avoid getaway crimes. We also determined the 10 safest neighborhoods and the 10 unsafest neighborhoods in Pittsburgh according to these metrics.

## Team Members
- Adam Wipprecht <amw290@pitt.edu>
- Roy Wu <row64@pitt.edu>

## Datasets
- [Pittsburgh Police Arrest Data](https://data.wprdc.org/dataset/arrest-data)
	- It includes information from Pittsburgh Police about arrests from 2016 to current. Some of the fields it contains are: Incident Location (Neighborhood, Address, Coordinates), Arrest Location (Address Only), Time of Arrest, Demographics of Suspect (Age, Race, Gender), and Offenses/Crimes.

- [Pittsburgh Speed Hump Data](https://data.wprdc.org/dataset/city-of-pittsburgh-speed-humps)
	- This data set contains information about the speed humps installed by the City of Pittsburgh. The dataset is maintained by Matthew Jacob and it falls under the Transportation data category. Some fields that it contains are: Speed Hump ID, Street Location, Neighborhood Location, Coordinates, Districts, and Wards. 	 
