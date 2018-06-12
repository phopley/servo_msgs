# servo_msgs
ROS Servo control messages.
## servo_array.msg
This message contains two elements
- uint8 index
- uint16 angle  
`index` references the servo that the angle is for, e.g. 0, 1, 2 or 3.  
`angle` is the angle to set the selected servo to.
## pan_tilt.msg
This message contains two elements
- int16 pan
- int16 tilt  
`pan` is the angle for the pan servo.  
`tilt` is the angle for the tilt servo.
