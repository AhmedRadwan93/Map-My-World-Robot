# Map-My-World-Robot
## Created The Following Files:

- mapping.launch
- teleop.launch
- localization.launch

>>Created a 2D occupancy grid and 3D octomap from a the simulated environment I created using my own robot with the RTAB-Map package.
>>
>>I used the rtabmap_ros package, which is a ROS wrapper (API) for interacting with RTAB-Map.
>>
>>I generated the appropriate launch files to launch the robot and map its surrounding environment.
>>
>>When the robot is launched  I teleoperated around the room to generate a proper map of the environment.

## Conclusion:

- The environment  have clear features and geometric shapes to perform mapping.

- The  map  contains at least 3 loop closures and the occupancy grid is identifiable.

- The characteristics of the landmark features are displayed
