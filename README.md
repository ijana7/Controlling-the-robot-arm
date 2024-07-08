<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ٢ ٢٩ ٠٢ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/16e66845-ac1c-491d-bee8-1ac6f35a7426"># Controlling-the-robot-arm
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
Compil
e the package
$ catkin_make

<img width="1667" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ١١ ٤٢ ١٧ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/f00dae1d-47ae-4a9a-b589-197e6a432e29">

<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ١١ ٤٢ ٣٠ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/467053c4-c827-4d86-bcda-16b00bcbd359">


![Uploading ‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ١١.٤٣.٠٨ م.png…]()

<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ١١ ٤٦ ١٥ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/55cba668-a32e-469b-a4f9-dfb450ae2369">

![Uploading ‏لقطة الشاشة ١٤٤٦-٠١-٠٢ في ٢.٢٨.٣٧ م.png…]()








