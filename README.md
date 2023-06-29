This repository was created to inspect and model real traffic in the city of 
Minneapolis, MN using data from different government sources to include
vehicle capacity per day, foor traffic trips in the city, and data from
the Metropolitian Council in an effort to test a new type of city grid
overlay called "Remove Three". There is a document in this repo that explains
more of this as well as serving as the basis for a letter to legistature of
Minnesota, the Metropolitian Council, and the city council of Minneapolis.

The goal of this project is to increase pedestrian safety regardless of
weather and placement within the city of Minneapolis. But in an attempt
to quell fears of a transit/bike takeover an attempt is made to save all
current street parking placements, furthermore, the basis of this is to
provide a plan that benefits all forms of traffic in the city in a
demonstrable and detectable fashion. I am unsure if this "Remove Three"
plan will work but I hope it does as doing so would increase safety,
reduce congestion, and improve air quality, improve bicycle safety,
provide for accodations for winter/northern cities, improve transit in the
city of Minneapolis.

This project also is attempting to create an extremely easy to implement
system with as few costs for the city as possible and to rely on already
existing public works department utilities (such as just using signs and 
lines)

Here is what I have done:
1. Isolated the city of Minneapolis using OSM and JOSM to create a grid of
bare streets of the city.
2. imported the city streets of Minneapolis to OSM. 
3. Collected all of the raw data needed for this project to work

What needs to be done:
1. A python script that is able to merge all of the data from the raw sources
in a fashion that is useful for SUMO must be created.
2. A comparison of the regular simulation of traffic should be made comparing

a. the transit times, on-time-performance of transit
b. the placements of bike-to-car interactions should be counted
c. Average speed of vehicles in the city should be measured (it should be as 
close to 20mph for safety reasons) a decrease in average vehicle speed should
be a desired.
d. commute times for regular trips for a vehicle.
e. frequency of traffic jams should be counted.
f. Among any other perhaps interesting analysis can be added as well

