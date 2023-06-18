# Road-Network-Analysis-and-Traffic-Flow-Simulation

In this project, I have implemented a simplified model of a road network and developed solutions to four different problems related to traffic simulation. Here's a summary of what has been done so far:

#Road Network Model:
Created a function load_road_network(filename) that parses a file containing the road network information. It builds dictionaries representing intersections and roads, based on the provided data file structure.

#Travel Time Calculation:
Implemented the function path_cost(path, intersections, road_times) to calculate the travel time of a vehicle through the road network. It determines whether a vehicle can traverse a given path without being stopped at any intersections and returns the total number of timesteps taken if possible.

#Intersection Analysis:
Developed the function intersection_step(intersections, road_times, intersection_id, cars_at_intersection, timestep). It processes a single step through time at a given intersection, identifying which vehicles can pass through the intersection at the current timestep based on their arrival times.

#Traffic Simulation:
Created the function simulate(intersections, road_times, cars_to_add) to simulate the movement of vehicles through the road network. The function tracks the position of each vehicle at each timestep, starting from timestep 0, and returns a list of actions representing what each car is doing at each timestep.

#Project Highlights:

Built a simplified model of a road network, focusing on intersections and traffic behavior.
Implemented algorithms to calculate travel time, identify vehicles' movements at intersections, and simulate traffic flow.
Demonstrated problem-solving skills in handling complex road network scenarios and provided a complete solution to the traffic simulation problem.
