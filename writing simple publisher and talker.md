# week6
## For the beginning of the task you need to open preveous task folder.
```
cd ros2_foxy/src/py_pubsub/py_pubsub
```
#by copying this you will add the publisher member function
```
wget https://raw.githubusercontent.com/ros2/examples/foxy/rclpy/topics/minimal_publisher/examples_rclpy_minimal_publisher/publisher_member_function.py
```
#at this stage you will see the differences ofd the files. Open the file folder and then you will see the new file at the py_pubsub file.
```
colcon build --packages-select py_pubsub
```
```
Starting >>> py_pubsub
[1.074s] WARNING:colcon.colcon_core.shell:The following packages are in the workspace but haven't been built:
- ament_lint
- ament_package
- ament_cmake_core
- ament_flake8
- ament_cmake_export_definitions
- ament_cmake_export_include_directories
- ament_cmake_export_libraries
- ament_cmake_export_link_flags
- ament_cmake_include_directories
- ament_cmake_libraries
- ament_cmake_python
- ament_cmake_version
- ament_pep257
- ament_cmake_export_dependencies
- ament_cmake_export_interfaces
- ament_cmake_export_targets
- ament_cmake_target_dependencies
- ament_cmake_test
- ament_copyright
- ament_cmake
- ament_cmake_gtest
- ament_cmake_pytest
- ament_index_python
- domain_coordinator
- ament_cmake_gmock
- rpyutils
- ament_cmake_ros
- fastrtps_cmake_module
- python_cmake_module
- rmw_implementation_cmake
- rosidl_adapter
- rosidl_typesupport_interface
- spdlog_vendor
- rosidl_parser
- rosidl_runtime_cpp
- tracetools
- rcutils
- rosidl_cmake
- rcpputils
- rosidl_runtime_c
- libyaml_vendor
- rcl_logging_spdlog
- rmw
- rosidl_generator_c
- rosidl_typesupport_introspection_c
- rcl_yaml_param_parser
- rosidl_typesupport_fastrtps_cpp
- rosidl_typesupport_introspection_cpp
- rosidl_typesupport_fastrtps_c
- rosidl_typesupport_c
- rosidl_generator_py
- rosidl_typesupport_cpp
- rosidl_default_runtime
- builtin_interfaces
- rmw_dds_common
- rcl_interfaces
- rmw_fastrtps_shared_cpp
- rosgraph_msgs
- statistics_msgs
- std_msgs
- rmw_fastrtps_cpp
- rmw_implementation
- rcl
- libstatistics_collector
- rclcpp
They are being used from the following locations instead:
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
- /opt/ros/humble
To suppress this warning ignore these packages in the workspace:
--packages-ignore ament_lint ament_package ament_cmake_core ament_flake8 ament_cmake_export_definitions ament_cmake_export_include_directories ament_cmake_export_libraries ament_cmake_export_link_flags ament_cmake_include_directories ament_cmake_libraries ament_cmake_python ament_cmake_version ament_pep257 ament_cmake_export_dependencies ament_cmake_export_interfaces ament_cmake_export_targets ament_cmake_target_dependencies ament_cmake_test ament_copyright ament_cmake ament_cmake_gtest ament_cmake_pytest ament_index_python domain_coordinator ament_cmake_gmock rpyutils ament_cmake_ros fastrtps_cmake_module python_cmake_module rmw_implementation_cmake rosidl_adapter rosidl_typesupport_interface spdlog_vendor rosidl_parser rosidl_runtime_cpp tracetools rcutils rosidl_cmake rcpputils rosidl_runtime_c libyaml_vendor rcl_logging_spdlog rmw rosidl_generator_c rosidl_typesupport_introspection_c rcl_yaml_param_parser rosidl_typesupport_fastrtps_cpp rosidl_typesupport_introspection_cpp rosidl_typesupport_fastrtps_c rosidl_typesupport_c rosidl_generator_py rosidl_typesupport_cpp rosidl_default_runtime builtin_interfaces rmw_dds_common rcl_interfaces rmw_fastrtps_shared_cpp rosgraph_msgs statistics_msgs std_msgs rmw_fastrtps_cpp rmw_implementation rcl libstatistics_collector rclcpp
[1.074s] ERROR:colcon.colcon_ros.task.ament_python.build:Failed to find the following files:
- /home/beka/ros2_foxy/src/install/cyclonedds/share/cyclonedds/package.sh
- /home/beka/ros2_foxy/src/install/fastcdr/share/fastcdr/package.sh
- /home/beka/ros2_foxy/src/install/gtest_vendor/share/gtest_vendor/package.sh
- /home/beka/ros2_foxy/src/install/gmock_vendor/share/gmock_vendor/package.sh
- /home/beka/ros2_foxy/src/install/foonathan_memory_vendor/share/foonathan_memory_vendor/package.sh
- /home/beka/ros2_foxy/src/install/connext_cmake_module/share/connext_cmake_module/package.sh
- /home/beka/ros2_foxy/src/install/fastrtps/share/fastrtps/package.sh
- /home/beka/ros2_foxy/src/install/rcl_logging_log4cxx/share/rcl_logging_log4cxx/package.sh
- /home/beka/ros2_foxy/src/install/rcl_logging_noop/share/rcl_logging_noop/package.sh
- /home/beka/ros2_foxy/src/install/rosidl_generator_dds_idl/share/rosidl_generator_dds_idl/package.sh
- /home/beka/ros2_foxy/src/install/rmw_connext_shared_cpp/share/rmw_connext_shared_cpp/package.sh
- /home/beka/ros2_foxy/src/install/rosidl_typesupport_connext_cpp/share/rosidl_typesupport_connext_cpp/package.sh
- /home/beka/ros2_foxy/src/install/rosidl_typesupport_connext_c/share/rosidl_typesupport_connext_c/package.sh
- /home/beka/ros2_foxy/src/install/rmw_connext_cpp/share/rmw_connext_cpp/package.sh
- /home/beka/ros2_foxy/src/install/rmw_cyclonedds_cpp/share/rmw_cyclonedds_cpp/package.sh
- /home/beka/ros2_foxy/src/install/rmw_fastrtps_dynamic_cpp/share/rmw_fastrtps_dynamic_cpp/package.sh
Check that the following packages have been built:
- cyclonedds
- fastcdr
- gtest_vendor
- gmock_vendor
- foonathan_memory_vendor
- connext_cmake_module
- fastrtps
- rcl_logging_log4cxx
- rcl_logging_noop
- rosidl_generator_dds_idl
- rmw_connext_shared_cpp
- rosidl_typesupport_connext_cpp
- rosidl_typesupport_connext_c
- rmw_connext_cpp
- rmw_cyclonedds_cpp
- rmw_fastrtps_dynamic_cpp
Failed   <<< py_pubsub [0.02s, exited with code 1]

Summary: 0 packages finished [0.81s]
  1 package failed: py_pubsub
```

```
beka@beka-virtual-machine:~/ros2_foxy/src/py_pubsub$ colcon build --packages-select py_pubsub
Starting >>> py_pubsub
--- stderr: py_pubsub                   
/usr/lib/python3/dist-packages/setuptools/command/install.py:34: SetuptoolsDeprecationWarning: setup.py install is deprecated. Use build and pip and other standards-based tools.
  warnings.warn(
---
Finished <<< py_pubsub [0.78s]

Summary: 1 package finished [0.93s]
  1 package had stderr output: py_pubsub
```
## From this point you can see that there is a new file named as py_pubsub
## Now run this code
```
ros2 run py_pubsub talker 

```
## Output for this will be.
```
[INFO] [1664850544.329996210] [minimal_publisher]: Publishing: "Hello World: 0"
[INFO] [1664850544.821959581] [minimal_publisher]: Publishing: "Hello World: 1"
[INFO] [1664850545.322347815] [minimal_publisher]: Publishing: "Hello World: 2"
[INFO] [1664850545.822956765] [minimal_publisher]: Publishing: "Hello World: 3"
[INFO] [1664850546.322339652] [minimal_publisher]: Publishing: "Hello World: 4"
[INFO] [1664850546.821889290] [minimal_publisher]: Publishing: "Hello World: 5"
[INFO] [1664850547.322529502] [minimal_publisher]: Publishing: "Hello World: 6"
[INFO] [1664850547.822593891] [minimal_publisher]: Publishing: "Hello World: 7"
[INFO] [1664850548.321717629] [minimal_publisher]: Publishing: "Hello World: 8"
[INFO] [1664850548.822190574] [minimal_publisher]: Publishing: "Hello World: 9"

```
## The next step is to show how listener.

```
ros2 run py_pubsub listener
```

```
[INFO] [minimal_subscriber]: I heard: "Hello World: 10"
[INFO] [minimal_subscriber]: I heard: "Hello World: 11"
[INFO] [minimal_subscriber]: I heard: "Hello World: 12"
[INFO] [minimal_subscriber]: I heard: "Hello World: 13"
[INFO] [minimal_subscriber]: I heard: "Hello World: 14"
```
