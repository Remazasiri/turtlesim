## Requirements
- ROS2 (Humble, Foxy, or newer)
- turtlesim package installed

## Installation
```bash
sudo apt install ros-humble-turtlesim
```

## Build the package
```bash
cd ~/ros2_ws/src
git clone <YOUR_REPO_URL>
cd ~/ros2_ws
colcon build
source install/setup.bash
```

## Run turtlesim
```bash
ros2 run turtlesim turtlesim_node
```

## Run the controller script
In another terminal:
```bash
ros2 run turtlesim_controller move_turtle
```
