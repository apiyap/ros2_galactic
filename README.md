# ROS2 GALACTIC RELEASE 





. ~/ros2_galactic/install/local_setup.bash

vcs import src < addons_ros2.repos

export MAKEFLAGS="-j6"
colcon build --symlink-install --parallel-workers 6
