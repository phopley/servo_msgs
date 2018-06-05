# servo_msgs
ROS Servo control messages.

## servo_array_msg
This message contains two elements
- uint8 index
- uint16 angle

`index` references the servo that the angle is for, e.g. 0, 1, 2 or 3.
`angle` is the angle to set the selected servo to.

