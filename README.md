# crazyflies_wiki

This wiki serves as a source of information about crazyflies bundle we use in LARICS Laboratory to students and researchers. It contains overview of students' projects with crazyflies and instructions on how to use the belonging equipment in the lab alongside the:  
* [docker](https://github.com/larics/docker_files/tree/master/ros2/ros2-humble/crazyflies-sitl) with CrazySim SITL and crazyswarm2 ROS2 package. Ubuntu 22.04. and ROS2 Humble based with ros1 bridge option
* [docker](https://github.com/larics/docker_files/tree/master/ros2/ros2-jazzy/crazyflies) with the latest crazyflies-firmware, cfclient and crazyswarm2 ROS2 package to communicate with or to deploy your code on the real crazyflies. Ubuntu 22.04. and ROS2 Jazzy based

# students' projects: 
* Formation changes (choreography) in different localization systems: loco positioning and optitrack [video](link to video)
* Consensus based formation control (Multi Robot Systems course - project) [video](link to video)
* Inspection trajectory for a small UAV [video](link to video)
* Navigation of the UAV in 3D space using semantics [video-simulation](link to video), [video-experiments](link to video)

# simulation:
To develop the code, it is first recommended to use the simulation docker. It is based on the CrazySim Software in the Loop Simulator integrated with Gazebo physics engine and sensors. The basic instruction on CrazySim can be found [here](link). If a user wants to develop code in ROS2 based package it is possible by using [crazywarm2](link) package. Detailed instructions on crazyflies can be found [here](link). Also the detailed setup of the docker can be found in the readme (link to readme).

# hardware:
To further deploy your code on crazyflies, you can use docker setup with the latest firmware. The detailed instructions are given in the readme (link to readme). 

-the equipment

-cfclient
-joystick ctrl
-loco positioning 
-optitrack
-optical flow 
-AI deck - jlink, change the access point
-multi ranger deck
-LED deck

Spare parts
charging crazyflies

couple of resolved and unresolved problems:
