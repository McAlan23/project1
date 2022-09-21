# project1
the first project1.

[Screencast from 2022년 09월 20일 11시 37분 15초.webm](https://user-images.githubusercontent.com/91641488/191155034-4bfc8091-f171-49de-ab67-3c5d331a4abc.webm)

Demo-video number one.

[Screencast from 2022년 09월 20일 11시 37분 15초.webm](https://user-images.githubusercontent.com/91641488/191156770-54a3151d-fb6f-46b7-a352-c63734b97730.webm)

Demo-video number two.
![Screenshot from 2022-09-20 11-51-53](https://user-images.githubusercontent.com/91641488/191156784-c74f9729-ecff-4208-9d3e-e0f75eb34bbb.png)

Screenshot that shows how it works.

1.beka@beka-virtual-machine:~$ rqt

2.beka@beka-virtual-machine:~$ ros2 run turtlesim turtlesim_node

3.Warning: Ignoring XDG_SESSION_TYPE=wayland on Gnome. Use QT_QPA_PLATFORM=wayland to run on Wayland anyway.
[INFO] [1663733476.577524905] [turtlesim]: Starting turtlesim with node name /turtlesim
[INFO] [1663733476.580853171] [turtlesim]: Spawning turtle [turtle1] at x=[5.544445], y=[5.544445], theta=[0.000000]
[INFO] [1663733538.414393359] [turtlesim]: Spawning turtle [tutrle123] at x=[10.000000], y=[3.000000], theta=[0.000000]
^C[INFO] [1663733561.194649277] [rclcpp]: signal_handler(signum=2)

5.beka@beka-virtual-machine:~$

6.beka@beka-virtual-machine:~$ ros2 node info /my_turtle

7./my_turtle

8.Subscribers:
    /my_turtle/cmd_vel: geometry_msgs/msg/Twist
    /parameter_events: rcl_interfaces/msg/ParameterEvent
    /turtle1/cmd_vel: geometry_msgs/msg/Twist

9.Publishers:
    /my_turtle/color_sensor: turtlesim/msg/Color
    /my_turtle/pose: turtlesim/msg/Pose
    /parameter_events: rcl_interfaces/msg/ParameterEvent
    /rosout: rcl_interfaces/msg/Log
    /turtle1/color_sensor: turtlesim/msg/Color
    /turtle1/pose: turtlesim/msg/Pose

10. Service Servers:
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

11. Service Clients:


12.Action Servers:
    /my_turtle/rotate_absolute: turtlesim/action/RotateAbsolute
    /turtle1/rotate_absolute: turtlesim/action/RotateAbsolute
  Action Clients:
