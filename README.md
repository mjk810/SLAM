# SLAM
<p>This repository contains an example of graph SLAM for simultaneous localization and mapping completed as part of the Udacity Computer Vision Nanodegree. I implemented the sense function in robot_class.py to determine the location of a landmark if the robot was able to sense landmarks based on their distance from the robot's current position. I also implemented the SLAM function. This implementation of graph SLAM uses a 2D array to store the weights for the robot and landmark x,y positions, and a 1D array to store the actual locations. The locations and weights are updated iteratively, and the final locations are computed by multiplying the inverse of the weight matrix by the position array. All other helper functions were provided as part of the course</p>

<p>Example of the 2D matrix of position weights for a 5x5 world (code to visualize provided by Udacity)</p>
<img src="https://user-images.githubusercontent.com/17497237/117587993-be84a080-b0ee-11eb-80c1-40125a9ee6c4.png" height="250px">

<p>Example of the 1D matrix of positions (code to visualize provided by Udacity)</p>
<img src="https://user-images.githubusercontent.com/17497237/117588048-0c010d80-b0ef-11eb-9656-5ee644001586.png" height="250px">

