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

we will run $roslaunch robot_arm_pkg check_motors.launch 
and press on graphical tools:


<img width="776" alt="Screen Shot 1443-01-03 at 4 02 47 PM" src="https://user-images.githubusercontent.com/53026144/129044492-8ecdf262-eb56-494e-b04c-da5bec405c6d.png">




we also open another shall web and run $roslaunch robot_arm_pkg check_motors_gazebo.launch
rosrun robot_arm_pkg joint_states_to_gazebo.py  and press  gazebo 

:<img width="776" alt="Screen Shot 1443-01-03 at 4 49 55 PM" src="https://user-images.githubusercontent.com/53026144/129045304-fc1f4aad-3918-4c11-8cdd-c27d4ae770e5.png">


for the arm will using movelt which is simulate the arm movement in different directions use
$roslaunch moveit_pkg demo.launch


<img width="776" alt="Screen Shot 1443-01-03 at 4 02 47 PM" src="https://user-images.githubusercontent.com/53026144/129046946-04cd352b-c445-4837-877d-db0b2d79ba9c.png">




My work https://app.theconstructsim.com/#/Rosject/449682




















