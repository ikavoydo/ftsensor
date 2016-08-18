# ftsensor
Drivers for IIT-ICub FTSens Force/Torque Sensor + ROS Connection.

As a light-weight (xxxgr) and low cost (xxxEU) 6D, stain-gauge based Force/Torque (F/T) sensor, the IIT's FTSens conventionally used in ICubs is a suitable candidate for Quadrotor VTOLs for measuring the external wrench when they are physically interacting with their environment. At least, they can definitely be used for the scientific purpose, even onboard of the quadrotor vtols, e.g. mikrokopter.de.

In the time when I decided to use this sensor, I could not find a straight forward way of acquiring the data and use it in ROS. The sensor outputs its data to the CAN protocol, hence I wrote a driver including:

1- CANBUS-Serial (USB) communication

2- Serial-ROS communication

I share the code here, for the convenience of the community.
