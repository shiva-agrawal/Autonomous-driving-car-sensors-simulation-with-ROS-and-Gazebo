# Autonomous driving car sensors' simulation with ROS and Gazebo

To develop any new robotic system may be mobile robot, robotic arm, aerial robot, etc., it is impotant to simulate it in the virtual environment with maximum possible real time capabilities. This includes development of ROBOT models, their kinematic and dynamic behaviours, sensors and controllers of the robot and the surrounding environment. 

This project is focussed towards the simulation of the sensors used in self driving cars for perception and localization. Gazebo simulator is used for the simulation along with Rviz tool. ROS kinetic is used for the developement along with Linux (Ubuntu 16.04). 

Following sensors are simulated under this project:

1.	Velodyne (HDL-32E and VLP-16)
2.	Mono camera
3.	Stereo camera
4.	GPS
5.	IMU
6.	Ultrasonic sensor

Apart from velodynes, other sensor models are first created using xacro files for gazebo and then are simulated using ROS launch files. Please note that, the sensor models are not the part of the development of this project and hence are not completely written by me. I have used the references and books to get the model codes. The main aim of the project is to understand, simulate and get insight of each sensor working and measurement data in ROS environment. Hence the simulation and testing of each sensor is done extensively as the part of the project which is also explained in the project report under doc section.


## Project Folder structure

1. docs 
    * Project details.pdf - detailed project report covering hardware and software description
    
2. src
    * autonomous_driving_sensors_simulation_in_ROS - ROS package containing all the xacro and launch files of the project
    
3. test (png files of simulations)
    * HDL-32E velodyne data visulaization with Obstacles in Rviz
    * VLP-16 Velodyne data visualization with obstacles in Rviz
    * mono_camera in gazebo
    * stereo camera simulation with gazebo
    * gps_sensor in gazebo
    * gps topics list 
    * gps sensor measurement
    * imu measurement
    * imu topic 
    * Ultrasonic_sensor_distance_measurement_01
    * ultrasonic_sensor_distance_measurement_02
