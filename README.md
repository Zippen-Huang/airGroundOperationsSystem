# airGround_OperationsSystem
Mecanum car follow the black cable, simutaneously avoiding obstacles, and a UAV follow it.  
![Image text](https://github.com/Zippen-Huang/airGroundOperationsSystem/blob/master/test.jpg)

HardWare:   
Mecanum car: Intel NUC and STM32F103, Intel Realsense  
UAV: Pixhawk and USB cam  
  
SoftWare:  
Follow the black cable function based on opencv, using depth image to avoid obstacles on the line   
UAV follow the qr code on the top of car by AprilTags   
link: AprilTags for ROS http://wiki.ros.org/apriltags_ros
