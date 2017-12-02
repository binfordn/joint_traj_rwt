# joint_traj_rwt

A simple HTML slider that sends trajectory_msgs/JointTrajectory messages with Robot Web Tools' roslibjs:
https://github.com/RobotWebTools/roslibjs

Written completely in HTML and JavaScript, so there is no need for a back end republisher.

Requires the roslib.js library, which can be found at:
https://github.com/RobotWebTools/roslibjs/blob/develop/build/roslib.js

The range of the slider should be adjusted based on the range of the joint being controlled.

Usage:
1. roslaunch rosbridge_server rosbridge_websocket.launch port:=<port_number>
2. Open joint_trajectory_slider.html in your browser
