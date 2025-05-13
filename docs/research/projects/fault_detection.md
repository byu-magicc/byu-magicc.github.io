# Fault Detection

In order for UAVs to gain access to the National Airspace System (NAS), and to be more reliable in general, they must be capable of greater self-awareness. The ability to detect whether sensors are functioning properly is an important part of this increased self-awareness. In the case of smaller UAVs, which are limited by size, weight and power (SWAP) constraints, it is not possible to carry redundant sensors onboard for simple voting scheme fault detection methods. The fault detection research taking place in the MAGICC Lab focuses on the development of a method that is capable of fault detection without recourse to redundant sensors.

This method is currently under development and is being tested under two different scenarios. The first scenario is a height-above-ground (HAG) sensing scenario using a laser rangefinder. Other sensors available on the platform include a forward-looking RGB-D camera and an IMU. Using these two other sensors, faults in the laser rangefinder must be detected. Preliminary experimental results look promising and the method is being refined and will be implemented for real-time fault detection onboard a rotorcraft UAV. The second scenario is detecting GPS spoofing or faults using an RGB camera and an elevation map. An optical flow field can be computed from the video and compared against an idealized motion field computed from the motion of the aircraft and the elevation map. This could detect differences between actual motion and GPS readings when a spoofing attack begins. It also has the potential to detect differences in terrain if a spoofing attack has already succeeded in diverting the aircraft to a new location.

## Personnel
- Brandon Cannon
- Brandon Carroll
- Dr. Tim McLain
- Dr. Randy Beard

## Sponsor
Project Duration
Publications

