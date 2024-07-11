## Controlling the robot arm by joint_ state_publisher 

## First we must follow these Commands

# $ roslaunch robot_arm_pkg check_motors.launch

The command `roslaunch robot_arm_pkg check_motors.launch` is used to launch a ROS (Robot Operating System) node or set of nodes defined in the `check_motors.launch` file, which is part of the `robot_arm_pkg` ROS package.

<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٤ ٣٣ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/c7094e95-a7b5-4de9-bf5c-9ea29d26a457">

# $ roslaunch robot_arm_pkg check_motors_gazebo.launch

This command is used to launch a set of ROS nodes and configurations defined in the `check_motors_gazebo.launch` file, which is part of the `robot_arm_pkg` ROS package. 

<img width="1704" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٥ ٠١ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/52565302-55ba-4a70-b96c-11b81d587721">

# $ rosrun robot_arm_pkg joint_states_to_gazebo.py

this command like to facilitate the integration between the ROS software and the Gazebo simulation environment for the robot arm.

<img width="1697" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٦ ٠٠ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/c34082fd-a623-40b2-ae60-a3e2e8ba409f">

## Controlling the robot arm by Moveit and kinematics

 ## roslaunch moveit_pkg demo_gazebo.launch
 
 this command allows you to quickly set up a demonstration environment where you can explore and test the integration of MoveIt! with a simulated robot in the Gazebo  environment. 
 <img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٦ ٤٠ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/93f2995b-cdad-4362-abc4-c4a44603d487">


<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٦ ٤٩ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/0aa8693c-cb9c-4474-8cab-d3cff7e93a4a">


<img width="1710" alt="‏لقطة الشاشة ١٤٤٦-٠١-٠٥ في ٧ ٥٦ ٥٩ م" src="https://github.com/ijana7/Controlling-the-robot-arm/assets/173642526/9006f901-7b71-4b36-946c-48f1a90be5e7">
