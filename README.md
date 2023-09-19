# Autonomous-Plant-Watering-Robot

View Project :- https://www.youtube.com/watch?v=rginpMrmdkc

This project is about developing a plant watering robot. The goal is for the robot to water household plants autonomously. It should explore the unknown environment and build a map, and scan for possible candidate targets (plants) at the same time. It should validate the data with the user, through a friendly interface. Once the map is finalized, the robot should be able to navigate in the map and reach the plants avoiding obstacles, then water them according to the user's preferences.

This is an ongoing project on autonomous robot navigating in a unknown environment.

April-Tags are used to detect and indicate plants. April-Tags in free space are considered plants. There are however no plants simulated in ROS Gazebo.

April-Tags on walls are only used for robot localization (pose estimation).
