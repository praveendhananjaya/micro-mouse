# micro-mouse

A Micromouse is a small robotic vehicle designed to navigate its way through an unknown maze. It is an autonomous, battery-operated, and self-contained robot that utilizes maze-solving algorithms to find the optimal route with the shortest run time to the center of the maze.


![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/WhatsApp%20Image%202021-05-01%20at%202.47.12%20PM.jpeg?raw=true)

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/20190911175233.gif?raw=true)


## testing

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/test.gif?raw=true)

# PCB 

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/IMG-20180806-WA0007.jpg?raw=true)

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/IMG-20180806-WA0012.jpg?raw=true)


![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/Schematic_microMouse2019_2021-05-07.png?raw=true)


## ambient filtering



![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/Block_Diagram.png?raw=true)




## sensor placement

behavior that will cause the robot to move parallel to the obstacle and even move away from the goal if needed to move around a non-convex obstacle.

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/wall_follow.png?raw=true)





## Wall follower 

micromouse initial testing done by Wall following algorithm.(left-hand rule or the right-hand rule)If the maze is simply connected, that is, all its walls are connected together or to the maze's outer boundary, then by keeping one hand in contact with one wall of the maze the solver is guaranteed not to get lost and will reach a different exit if there is one; otherwise, the algorithm will return to the entrance having traversed every corridor next to that connected section of walls at least once. The algorithm is a depth-first in-order tree traversal.


![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/right_al.gif?raw=true)


## flood fill

shorted path selected by flood fill. Flood fill, also called seed fill, is an algorithm that determines and alters the area connected to a given node in a multi-dimensional array with some matching attribute. ... Note that flood filling is not suitable for drawing filled polygons, as it will miss some pixels in more acute corners

![alt text](https://github.com/praveendhananjaya/micro-mouse/blob/main/doc/flood_fill.gif?raw=true)

