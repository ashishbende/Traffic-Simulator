# Traffic-Simulator
A traffic simulation in which vehicles are moving along streets and are crossing intersections.
With the increasing traffic in the city, traffic lights are needed for road safety. Each intersection therefore is equipped with a traffic light. 
Simulating real world traffic, uing thread-safe communication protocol (such as mutexes, locks and message queues) between vehicles and intersections.

## Dependencies

* cmake >= 2.8
* make >= 4.1  
* OpenCV >= 4.1
* gcc/g++ >= 5.4
 

## Basic Build Instructions

1. Clone the repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./traffic_simulation`.