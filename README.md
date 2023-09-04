# SLAM-Landmark-Detection-and-Tracking

## Description

In this project, I localized a robot on a 2D world using simultaneous localization and mapping (SLAM) techniques to gather information from a robot's sensors and motions over time, and then use information about measurements and motion to re-construct a map of the world.

I have also accounted for a certain amount of uncertainty, as robot motion and sensors in the real world are rarely perfectly accurate. In this way, we cannot always perfectly predict the motion of a robot. What we can do, however, is take many data points and triangulate the location of different features and landmarks for more accurate readings. 

More details can be found in the following notebook files:

## Files

- `Notebook 1` : Robot moving and sensing
- `Notebook 2` : Omega and Xi, Constraints
- `Notebook 3` : Landmark detection and tracking
- `robot_class.py` : Robot object with its world, including a sense function that allows the robot to detect landmarks. 
- `helpers.py` : helper functions

