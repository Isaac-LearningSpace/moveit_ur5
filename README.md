# MoveIt UR5 Configuration

A MoveIt configuration package for Universal Robots UR5 arm.

## Requirements

- Ubuntu 22.04
- ROS 2 Humble

## Build

```bash
colcon build --symlink-install 
source install/setup.bash
```

## Usage

### Launch MoveIt Setup Assistant
```bash
ros2 launch moveit_setup_assistant setup_assistant.launch.py
```

### Generate URDF
```bash
xacro ur5.urdf.xacro > ur5.urdf
```

### Run MoveIt Demo
```bash
ros2 launch ur5_moveit_config demo.launch.py
```



## Reference

- https://www.youtube.com/watch?v=pGje2slp6-s