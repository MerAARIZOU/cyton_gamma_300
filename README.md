# cyton_gamma_300
ROS package for maipulating cyton_gamma_300 in Gazebo
# To launch the application
roslaunch cyton_gamma_300_gazebo cyton_gamma_300_world.launch

This work stills in progress, for some reason the arm is not stable after running cyton_gamma_300_control launch file (line 26 in cyton_gamma_300_control/launch/cyton_gamma_300_control.launch is a comment, just take off the comment tags and you'll see the result) I suspect that mass and inertia properties are not correct, I encourage you to improve it ;)

Special thanks to UNH-Robotics and Andras Fekete, all this package is based on their works.

