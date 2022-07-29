# Algorithm Dijkstra
Developed a route that does the least cost calculation using Dijkstra's algorithm.

-> First of all, follow the image "rota" for a better understanding of the activity.

### Description of Activity:

An application driver has been given a run to perform. The current location of the driver is represented below by vertex number 1 (one) and the race is at vertex number 5 (five). 

The graph above shows all the routes to reach the destination from the starting point. The destination of the race is the vertex indicated by vertex number 5 (five). The possible routes are represented by the other vertices ranging from 1 (one), which is the origin, to 4 (four).  

To develop an algorithm that helps the application pilot to make the best route decision, because due to the consecutive increase in fuel prices, the pilot wants an estimate of what is the best route to the race destination. To do this, a historical survey of the average consumption of trips passing through each point of origin to the final destination was done.   

In the graph, vertices 1, 2, 3, 4 and 5 represent, respectively, the routes that the pilot must follow to reach the destination. The route is represented by the connecting vertices (1 to 2), (1 to 3), (2 to 4), (2 to 5), and so on. The average consumption (weight) between each link is represented by X. You must replace the X by the first 7 digits of your AR (going from left to right) multiplied by 6.596, which is the value of the litre of petrol at that moment, in the sequence: (1-2), (1-3), (2-4), (2-5), (3-2), (3-5), (4-5).   

  
#### Example:   

RA 2045703-5 = The following numbers from your RA 2045703 will be used.   
RA 204570-5 = In case of 6 digits, add the digit 1 at the end of 2045701   
 
(1-2) = 2 * 6,596 = 13,192 
(1-3) = 0 * 6,596 = 0 
(2-4) = 4 * 6,596 = 26,384 

More Information:
I used the website "replit.com" to compile:
https://replit.com/@Kelly-Prone/mapaed1oficial#main.c
