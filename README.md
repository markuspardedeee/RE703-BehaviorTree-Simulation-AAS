# RE703-BehaviorTree-Simulation-AAS
Tugas Implementasi Behavior Tree pada Robot Patroli di Gazebo ROS untuk Mata Kuliah RE703

• Markus Pardede / 4222201063

• Bela Lisfatia / 4222201064

Case Study
A robot with two differential wheels on the right and left sides moves from one position to another in a forward or backward motion. This is simulated through a gazebo using a behavior tree algorithm.
Behaviour Tree Diagram
![WhatsApp Image 2026-01-19 at 17 31 07](https://github.com/user-attachments/assets/304ee9b9-9cb5-446c-9bb1-e877fc6e8109)

Running Instruction
1. Open Terminal
To run the robot simulation in the gazebo, run the following commands:

cd ~/gazebo_ws
source ~/gazebo_ws/install/setup.bash
source /opt/ros/humble/setup.bash
ros2 launch barabot launch_sim.launch.py

2. Open New Terminal
To run the behavior tree algorithm, run the following commands:

cd ~/gazebo_ws
source install/setup.bash
ros2 run barabot_bt bt_main

Demonstration Robot
https://www.youtube.com/watch?v=5vrrORMIICo
