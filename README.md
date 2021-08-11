# Robot-Arm-Project
This is Arm's Robot by using ROS



In this project will create and simulate an arm for robot using the operating system (ROS).
 by using this websit  https://www.theconstructsim.com 

After creating an account on this website we will create new  rosproject 
then we will open-shell web and  use all the  commands there:

$ cd ~/catkin_ws/src
$ sudo apt install git
$ git clone https://github.com/smart-methods/arduino_robot_arm


then Install all the dependencies:

$ rosdep install --from-paths src --ignore-src -r -y

$ sudo apt-get install ros-melodic-moveit

$ sudo apt-get install ros-melodic-joint-state-publisher ros-melodic-joint-state-publisher-gui

$ sudo apt-get install ros-melodic-gazebo-ros-control joint-state-publisher

$ sudo apt-get install ros-melodic-ros-controllers ros-melodic-ros-control


-Compile the package:


$ catkin_make

we will run $roslaunch robot_arm_pkg check_motors.launch:
<img width="776" alt="Screen Shot 1443-01-03 at 4 49 55 PM" src="https://user-images.githubusercontent.com/53026144/129044353-c204ef17-6f8b-4e1e-8f6d-03e5e297ed67.png">
