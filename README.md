# Optimal-Position-Algorithm
An attempt to develop an algorithm that optimizes the location of objects (called servers) that interact with other objects (called nodes) within a predefined range. The algorithm was implemented in python using numpy, pandas, matplotlib and seaborn.

### Glosary
- **Server**: An object that distributes a resources or interacts in some way with other objects within a specified (circular) range.
- **Node**  : An object that recieves a resources or requires some interaction.
- **Radius**: The "distance" around a server that determines how far away nodes can be before they are no longer served by the server.
- **Most connected object/node**: The node that has the highest number of nodes within a specified radius. This radius is the same as the radius defined above.   

### Demonstration
39 Nodes, 9 Servers 
![demo](https://user-images.githubusercontent.com/40518057/116802534-80c9bb80-aae1-11eb-8928-5a5c08189049.gif)

### Algotithm Flowchart
![image](https://user-images.githubusercontent.com/40518057/116802184-f97b4880-aade-11eb-98a5-99431f8338b0.png)

### Time Complexity
![image](https://user-images.githubusercontent.com/40518057/116802219-38a99980-aadf-11eb-9631-43a4c6e392e5.png)

### Proposed Applications:
- In general, any application that requires the distribution of resources within a limited range may benefit from this algorithm like this one. For example, this algorithm can help optimize the positions of…
  - surveillance drones used in disaster management endeavors like wildfire fighting.
  - wireless-communication infrastructure like cell-towers.
  - electrical substations
  - COVID-19 vaccination clinics

Preliminary analysis reveals that the number of circles depends on the radius of the circle and density of the points.

