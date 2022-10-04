# msg and srv


```
colcon build --packages-select tutorial_interfaces
```
## Opn another terminal

```
. install/setup.bash
ros2 interface show tutorial_interfaces/msg/Num
```
## the output will be:
```
int64 num
```
## the output shows that your code and all the step has been done properely 
```
ros2 interface show tutorial_interfaces/msg/Sphere
```
```
geometry_msgs/Point center
        float64 x
        float64 y
        float64 z
float64 radius
```

```
ros2 interface show tutorial_interfaces/srv/AddThreeInts
```

```
int64 a
int64 b
int64 c
---
int64 sum
```
