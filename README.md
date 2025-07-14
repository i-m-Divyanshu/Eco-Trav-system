This Java-based Electric Bus Routing System models a city's electric bus network. It allows users to:

View all available bus stations

Display the full route map with distances

Calculate the shortest distance and fare between any two stations using Dijkstra's algorithm

The system is built using a console interface and operates on real-time user input.

Main Features & Functions:

1.addStation(String stationName)

Adds a new station to the bus network.

2.addConnection(String source, String destination, int distance)

Creates a bidirectional route between two stations with the given distance.

3.displayStations()

Prints a list of all available bus stations.

4.displayBusMap()

Shows the full electric bus route map with connected stations and distances.

5.path(String source, String destination)

Uses Dijkstra's algorithm to compute the shortest distance between two stations.

6.Main Menu (inside main)

A looped interactive menu allowing users to choose actions like viewing stations, seeing the route map, or finding distances and fare.

