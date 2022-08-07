The objective of this assignment is to download & install the arm package

> Open "Terminal" in Ubuntu and copy & paste the following commands

> Replace each word (kinetic) with (noetic)
In all commands to make the commands work properly

> In step 21 replace (abdullah) with your username/account in the system


1- sudo apt-get update

2- apt-cache search ros-kinetic

3- echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc

4- source ~/.bashrc

5- sudo apt install python-rosdep

6- sudo rosdep init

7- rosdep update

8- sudo apt-get install ros-noetic-catkin

9- mkdir -p ~/catkin_ws/src

10- cd ~/catkin_ws/

11- catkin_make

12- cd ~/catkin_ws/src

13- git clone https://github.com/smart-methods/arduino_robot_arm.git 

14- cd ~/catkin_ws

15- rosdep install --from-paths src --ignore-src -r -y

16- sudo apt-get install ros-kinetic-moveit

17- sudo apt-get install ros-kinetic-joint-state-publisher ros-kinetic-joint-state-publisher-gui

18- sudo apt-get install ros-kinetic-gazebo-ros-control joint-state-publisher

19- sudo apt-get install ros-kinetic-ros-controllers ros-kinetic-ros-control

20- sudo nano ~/.bashrc

21- source /home/abdullah/catkin_ws/devel/setup.bash
Then (Ctrl + O) Then (Enter) Then (Ctrl + X)

22- source ~/.bashrc

23- roslaunch robot_arm_pkg check_motors.launch