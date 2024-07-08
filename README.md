# Controlling-the-robot-arm
Controlling the robot arm by joint_ state_publisher and Controlling the robot arm by Moveit and kinematics

Installing the package
arduino_robot_arm
- Add the “arduino_robot_arm” package to “src” folder
	$ cd ~/catkin_ws/src
	$ sudo apt install git
	$ git clone https://github.com/smart-methods/arduino_robot_arm 
- Install all the dependencies 
	$ cd ~/catkin_ws
	$ rosdep install --from-paths src --ignore-src -r -y
	$ sudo apt-get install ros-noetic-moveit
	$ sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui
	$ sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher
	$ sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control
Compile the package
$ catkin_make
