- ubuntu22.04
- ros2 humble


```
colcon build --symlink-install 
source install/setup.sh

ros2 launch moveit_setup_assistant setup_assistant.launch.py

ros2 launch ur5_moveit_config demo.launch.py 

xacro ur5.urdf.xacro > ur5.urdf

```