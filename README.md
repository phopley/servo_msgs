# servo_msgs

ROS Servo control messages.

## servo_array.msg

This message passes the position demand for a RC servo contained in an array of servos.

* `uint8 index`:  
  references the servo that the angle is for, e.g. 0, 1, 2 or 3 

* `uint16 angle`:  
  is the angle to set the selected servo to

## pan_tilt.msg

This message passes the pan and tilt position demands for a pan/tilt device

* `int16 pan`:  
  is the angle for the pan servo

* `int16 tilt`:  
  is the angle for the tilt servo
