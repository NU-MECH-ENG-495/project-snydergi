# Pathplanning in C++

For mobile robots, pathplanning is a major consideration in terms of which algorithm to use, if it is robust, and if it is efficient. 
I am interested in working with mobile robots for a career so understanding and implementing pathplanning is a necessity.
I have limited experience working with pathplanning in other friendlier, slower languages like Python, so increasing difficulty with new algorithms that couldn't be applied that is desired.
The project should also have a visualization aspect, as a planned path is not interesting without seeing it.
Dynamic obstacle avoidance and course correction will also be implemented to ensure it is robust to realistic environments and factors such as sensor drift.

My thoughts for implementing this are in two phases. First, I want to find at least three methods to investigate, with two being previously unknown to me. 
For example, I have done basic RRT in Python, but have no experience with methods like A* and Dijkstra.
I want to multithread these so I can run each option simultaneously and select whichever path finishes first, which will instigate my learning of multi-threaded calls which I have never done myself.
Additionally, for visualization, the planned paths will be fed to a simulated robot through ROS2 and simulated in an environment such as Gazebo.
