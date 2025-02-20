# underactuated-hands
This repo provides an open-source design for a three-finger underactuated robotic hand. The design is low-cost and readily reproducible using off-the-shelf components and 3D printing. Software is provided so that researchers can easily control the robotic hand, as well as get real-time sensory feedback.

CAD model can be downloaded from [here](https://stevens0-my.sharepoint.com/:u:/g/personal/lwang4_stevens_edu/EX47wA0kKBVOqwH9P3gvtv0BDL-9bCvxESM_y-H_IIvzmQ?e=briaRj).
![Screenshot 2024-05-08 110911](https://github.com/stevens-armlab/underactuated-hands/assets/20483987/ad626e04-1fcb-4a81-ad84-c8db43af08d0)

## Quickstart: Robotic Hand Teleoperation
1. Upload `underactuated_teleoperated_control_daisychain.ino` to the Teensy
2. Run `roslaunch hand_arduino hand.launch` to enable joy_node and ros/arduino communication
3. Run 'rosrun hand_arduino hand_teleop.py' to enable controlling the robotic hand via a gamepad controller
