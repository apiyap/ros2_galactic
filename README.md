# ROS2 GALACTIC RELEASE 


[Follow instruction](https://docs.ros.org/en/galactic/Installation/Ubuntu-Development-Setup.html)

Install addon packages
<pre>
. ~/ros2_galactic/install/local_setup.bash

vcs import src < addons_ros2.repos

export MAKEFLAGS="-j6"
colcon build --symlink-install --parallel-workers 6

</pre>

Summary: 383 packages finished [22min 54s]
  90 packages had stderr output: action_tutorials_py ament_clang_format ament_clang_tidy ament_copyright ament_cppcheck ament_cpplint ament_flake8 ament_index_python ament_lint ament_lint_cmake ament_mypy ament_package ament_pclint ament_pep257 ament_pycodestyle ament_pyflakes ament_uncrustify ament_xmllint async_web_server_cpp behaviortree_cpp_v3 demo_nodes_py domain_coordinator examples_rclpy_executors examples_rclpy_guard_conditions examples_rclpy_minimal_action_client examples_rclpy_minimal_action_server examples_rclpy_minimal_client examples_rclpy_minimal_publisher examples_rclpy_minimal_service examples_rclpy_minimal_subscriber examples_rclpy_pointcloud_publisher examples_tf2_py launch launch_ros launch_testing launch_testing_ros launch_xml launch_yaml nav2_gazebo_spawner nav2_simple_commander opencv_tests osrf_pycommon quality_of_service_demo_py ros2action ros2bag ros2cli ros2component ros2doctor ros2interface ros2launch ros2lifecycle ros2multicast ros2node ros2param ros2pkg ros2run ros2service ros2test ros2topic ros2trace rosidl_cli rosidl_runtime_py rpyutils rqt rqt_action rqt_bag rqt_bag_plugins rqt_console rqt_graph rqt_gui rqt_gui_py rqt_msg rqt_plot rqt_publisher rqt_py_console rqt_reconfigure rqt_service_caller rqt_shell rqt_srv rqt_top rqt_topic sensor_msgs_py sros2 test_launch_ros tf2_ros_py tf2_tools topic_monitor tracetools_launch tracetools_read tracetools_trace
