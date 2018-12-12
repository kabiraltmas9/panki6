# teleop_twist_keyboard
Generic Keyboard Teleop for ROS

# Launch
Run.
```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

With custom values.
```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py _speed:=0.9 _turn:=0.8
```

# Usage
```
Reading from the keyboard  and Publishing to Twist!
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   U    I    O
   J    K    L
   M    <    >

t : up (+z)
b : down (-z)

For Orientation mode:
---------------------------
        8     
   4    5    6
        2    

7 : roll left (-x)
9 : roll right (+x)

anything else : stop

q/z : increase/decrease max speeds by 10%
w/x : increase/decrease only linear speed by 10%
e/c : increase/decrease only angular speed by 10%

CTRL-C to quit
```

