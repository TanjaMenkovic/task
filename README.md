# 1 Load the data 
Load the data into the solution. Please mind the schema/data types of fields. 

# 2 Warmup 
How many trips/entries does the dataset contain? 
And how many unique bike ids? 

# 3 Trips 
Fields 
Bike id is Pyörän ID 
Trip length in meters is Matkan pituus m 
Questions 
Which three bikes had the least trips? How many trips did each have? Which three bikes had the most trips? How many trips did each have? Which three bikes travelled the least distance during the year? Show the distance in kilometers. 
Which bikes travelled over 4500 km during the season if any? 

# 4 Revenue
Trip revenue is Kokonaishinta 
Which bike made the most revenue? 

# 5 Maintenance 
Field is Huoltolainaus which is 1 for maintenance. 
Count top 5 most maintained bikes. How many times were they taken to maintenance? 

# 6 Distances 
Start coordinates are in Lainauksen koordinaatit and return coords are in Palautuksen koordinaatit. 
Latitude and longitude for both loans and returns are stuffed in a single field in the dataset. Split them into separate fields and add those new fields into the dataset as new fields preserving the originals. In addition, calculate the distance between start and end (in KM). 
Show 5 rows of the result 
Which bike was left farthest away from its starting point? 
What kind of discrepancies did you identify in the dataset while working with the coordinates, if any? 

# 7 Relational model 
Design a potential relational model (entity relationship diagram) for a database in which the database could be pushed. Tool choice is free.

https://dbdiagram.io/d/62f52813c2d9cf52fa8eb913
