# Pittsburgh Getaway Crimes
This project uses police arrest data and vehicle speed hump data from the Western Pennsylvania Regional Data Center to determine target neighborhoods in Allegheney County for getaway crimes. 

The project was completed in Jupyter Notebook and created with Python utilizing the Pandas data analysis framework, NumPy for mathematical operations, and matplotlib for embedded plots. Additionally, we used the positionstack API to calculate and estimate incident-to-crime locations.

## Community Safety Analytics: Identifying High-Risk Areas for Hit & Run Crimes

Utilizing the Pittsburgh Speed Hump Data, it was found that the neighborhoods Overbrook, Stanton Heights, and Central Oakland all have the lowest speedhump count (of 1), making it the best neighborhood for criminals/ getaway drivers and implying that it is the worst neighborhoods for the general public in that respect. We also found that Squirrel Hill was the best neighborhood for avoiding getaway drivers as it had 18 speed humps. Police Arrest Data was used to gauge the chances of catching criminal getaway drivers. The data was analyzed to indicate the level of police presence/ law enforcement activity through the amount of arrests, change in number of arrests, and the average distances of the arrests. Using these metrics, we found Squirrel Hill to be the best neighborhood in Pittsburgh to avoid criminal getaway drivers.

## Team Members
- Adam Wipprecht <amw290@pitt.edu>
- Roy Wu <row64@pitt.edu>

## Datasets
- [Pittsburgh Police Arrest Data](https://data.wprdc.org/dataset/arrest-data)
	- It includes information from Pittsburgh Police about arrests from 2016 to current. Some of the fields it contains are: Incident Location (Neighborhood, Address, Coordinates), Arrest Location (Address Only), Time of Arrest, Demographics of Suspect (Age, Race, Gender), and Offenses/Crimes.

- [Pittsburgh Speed Hump Data](https://data.wprdc.org/dataset/city-of-pittsburgh-speed-humps)
	- This data set contains information about the speed humps installed by the City of Pittsburgh. The dataset is maintained by Matthew Jacob and it falls under the Transportation data category. Some fields that it contains are: Speed Hump ID, Street Location, Neighborhood Location, Coordinates, Districts, and Wards. 	 
