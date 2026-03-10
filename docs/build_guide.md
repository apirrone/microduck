# Build guide 

Before mounting the motors, make sure to flash them with at least the correct ids and baudrate (1000000)

20:  left_hip_yaw
21:  left_hip_roll
22:  left_hip_pitch
23:  left_knee
24:  left_ankle
30:  neck_pitch
31:  head_pitch
32:  head_yaw
33:  head_roll
34:  mouth_motor
10:  right_hip_yaw
11:  right_hip_roll
12:  right_hip_pitch
13:  right_knee
14:  right_ankle

You can do it using the Dynamixel Wizard.

Take also the time to set the following parameters for each motor : 
- return delay time: 0
- baudrate: 1000000
- homing offset: 0
- pwm slope: 255
- shutdown: 52 <image>



## TODO 
- [x] wiring diagram
- build steps