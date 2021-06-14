# The Traveling Salesman Problem (TSP)
Coursework from University of Hertfordshire

## Task
The Traveling Salesman Problem (TSP) is a problem that tries to determine the shortest route to travel through a series of cities (visiting each one only once), returning to the city of origin. It is a difficult optimisation problem inspired by the need for sellers to deliver to different locations (cities), taking the shortest possible route, reducing the time needed for travel and possible transportation and fuel costs.
The algorithm implemented in this coursework is called the nearest neighbour algorithm.
The nearest neighbour algorithm is easy to implement and execute quickly, but it can sometimes miss shorter routes, which are easily noticed with human vision, due to its "greedy" nature. As a general guide, if the last steps of the route are comparable in length to those of the first steps, the route is reasonable. If they are much larger, then there are likely to have better routes.
In this coursework, we had a list of locations (cities), and we had to locate the nearest city. For this, we utilised a simple approach which was to take a city and calculate its distance from all the other cities. After obtaining the lowest value, consider that city that resulted in the lowest value, add its coordinates in another list organised by distance and delete the coordinate of that city from the original list. With this sequence, we managed to have a list in order of cities by the shortest distance.

## Contact me!

For more information about this project, please email me at mgrosmaninho@hotmail.com
