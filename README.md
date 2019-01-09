# servo_msgs

ROS Servo control messages.

## servo_array.msg

This message passes the position demand for a RC servo contained in an array of servos.

* `uint8 index`:  
  references the servo that the angle is for, e.g. 0, 1, 2 or 3 

* `uint16 angle`:  
  is the angle, in degrees, to set the selected servo to

