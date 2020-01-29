# IBM-Capstone-Project
City Planners guide to improve amenities based on growing population in Santa Clara County

Problem statement: The target audience for this problem are the City Planning commission who need a Data Scientist to identify locations in a particular county(in case of this project:Santa Clara) where public amenities need to be improved to better serve their county. To name a few of such amenities are:
1. Public Park
2. Library
3. Fire Station
4. Postal service 
5. Public transportation
6. Emergency Rooms/ Urgent care
7. School

Data Sources:
1. We will be using information from https://simplemaps.com/data/us-zips to obtain zipcode, lat/long, population density, name of the city.
2. We would then use Four Square to obtain the above amenities using categorical ids and categorize it based on the nearness to every zip code (5 mi/10mi,15mi/20mi radius).
3. We use this category to provide recommendation to the City Planning officials on locations of lacking/less accessible amentities for particular zipcode(s) and the degree of urgency of needed amenties based on various factors such as population density etc.
4. K map clustering will be used to find the clusters of amenties degree ( for eg: deg 1 if it is a well rounded/accessible locality and deg 5 for a poorly accessbile neighborhood) for each of the 7 amenities.
