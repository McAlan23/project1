# project1
the first project1
![Screenshot from 2022-09-20 11-30-46](https://user-images.githubusercontent.com/91641488/191154187-35dbae56-0660-4497-b161-0d4778046213.png)
![Screenshot from 2022-09-20 11-29-43](https://user-images.githubusercontent.com/91641488/191154236-2f855621-e527-4b1c-9a7a-cf449fbf12bb.png)
![Screenshot from 2022-09-20 11-28-57](https://user-images.githubusercontent.com/91641488/191154238-a4ea46e6-b4e9-44d1-be36-c947fbcfa0b1.png)
[Screencast from 2022년 09월 20일 11시 37분 15초.webm](https://user-images.githubusercontent.com/91641488/191155034-4bfc8091-f171-49de-ab67-3c5d331a4abc.webm)
[Screencast from 2022년 09월 20일 11시 37분 15초.webm](https://user-images.githubusercontent.com/91641488/191156770-54a3151d-fb6f-46b7-a352-c63734b97730.webm)
![Screenshot from 2022-09-20 11-51-53](https://user-images.githubusercontent.com/91641488/191156784-c74f9729-ecff-4208-9d3e-e0f75eb34bbb.png)
![Screenshot from 2022-09-20 11-51-34](https://user-images.githubusercontent.com/91641488/191156790-bb92218f-ba80-4491-baa0-44816de01cd4.png)
![Screenshot from 2022-09-20 11-50-23](https://user-images.githubusercontent.com/91641488/191156791-07ba326b-8afd-49e2-bacc-2687983363cc.png)
beka@beka-virtual-machine:~$ rqt
beka@beka-virtual-machine:~$ ros2 run turtlesim turtlesim_node
Warning: Ignoring XDG_SESSION_TYPE=wayland on Gnome. Use QT_QPA_PLATFORM=wayland to run on Wayland anyway.
[INFO] [1663733476.577524905] [turtlesim]: Starting turtlesim with node name /turtlesim
[INFO] [1663733476.580853171] [turtlesim]: Spawning turtle [turtle1] at x=[5.544445], y=[5.544445], theta=[0.000000]
[INFO] [1663733538.414393359] [turtlesim]: Spawning turtle [tutrle123] at x=[10.000000], y=[3.000000], theta=[0.000000]
^C[INFO] [1663733561.194649277] [rclcpp]: signal_handler(signum=2)
beka@beka-virtual-machine:~$ 
beka@beka-virtual-machine:~$ ros2 node info /my_turtle
/my_turtle
  Subscribers:
    /my_turtle/cmd_vel: geometry_msgs/msg/Twist
    /parameter_events: rcl_interfaces/msg/ParameterEvent
    /turtle1/cmd_vel: geometry_msgs/msg/Twist
  Publishers:
    /my_turtle/color_sensor: turtlesim/msg/Color
    /my_turtle/pose: turtlesim/msg/Pose
    /parameter_events: rcl_interfaces/msg/ParameterEvent
    /rosout: rcl_interfaces/msg/Log
    /turtle1/color_sensor: turtlesim/msg/Color
    /turtle1/pose: turtlesim/msg/Pose
  Service Servers:
    /clear: std_srvs/srv/Empty
    /kill: turtlesim/srv/Kill
    /my_turtle/describe_parameters: rcl_interfaces/srv/DescribeParameters
    /my_turtle/get_parameter_types: rcl_interfaces/srv/GetParameterTypes
    /my_turtle/get_parameters: rcl_interfaces/srv/GetParameters
    /my_turtle/list_parameters: rcl_interfaces/srv/ListParameters
    /my_turtle/set_parameters: rcl_interfaces/srv/SetParameters
    /my_turtle/set_parameters_atomically: rcl_interfaces/srv/SetParametersAtomically
    /my_turtle/set_pen: turtlesim/srv/SetPen
    /my_turtle/teleport_absolute: turtlesim/srv/TeleportAbsolute
    /my_turtle/teleport_relative: turtlesim/srv/TeleportRelative
    /reset: std_srvs/srv/Empty
    /spawn: turtlesim/srv/Spawn
    /turtle1/set_pen: turtlesim/srv/SetPen
    /turtle1/teleport_absolute: turtlesim/srv/TeleportAbsolute
    /turtle1/teleport_relative: turtlesim/srv/TeleportRelative
  Service Clients:

  Action Servers:
    /my_turtle/rotate_absolute: turtlesim/action/RotateAbsolute
    /turtle1/rotate_absolute: turtlesim/action/RotateAbsolute
  Action Clients:
