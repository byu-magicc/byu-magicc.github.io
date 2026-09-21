# Austin Stone

![](../assets/austin_stone.png){ width=350px }

---

- **Email**: abstone2@byu.edu
- **LinkedIn**: [linkedin.com/in/austin-stone-72823389](https://www.linkedin.com/in/austin-stone-72823389/)
- **ORCID**: [0009-0008-6960-7093](https://orcid.org/0009-0008-6960-7093)

## About

Austin is a PhD candidate in Electrical and Computer Engineering at Brigham Young University, advised by Dr. Cammy Peterson in the MAGICC Lab. His research focuses on thermal infrared (LWIR) perception for GPS-denied navigation, including thermal-inertial odometry, robust visual outlier rejection, uncertainty-aware optical flow, and thermal infrared single-object tracking.

Austin earned a BS in Mechanical Engineering from BYU with minors in Computer Science and Mathematics and began his research career as an undergraduate research assistant in the MAGICC Lab. He also works as a Senior Drone Algorithm Engineer at Teledyne FLIR on the Rogue One program, developing visual-inertial odometry and sensor fusion systems for an EO/IR imaging pipeline. Outside of research, he enjoys tinkering with home automation and self-hosted infrastructure.

## Research

### Thermal-Inertial Odometry

Austin develops real-time monocular thermal-inertial odometry for high-speed, GPS-denied flight. The system fuses a longwave infrared camera, high-rate IMU, laser range finder, barometer, and magnetometer in a fixed-lag factor graph. It runs onboard an NVIDIA Jetson Xavier NX and has sustained closed-loop quadrotor flight at 30 m/s with less than 2% drift over kilometer-scale trajectories.

### Robust Outlier Rejection

His work on visual outlier rejection introduces IMU-aided minimal solvers and on-manifold essential-matrix refinement for thermal-inertial odometry. In GPS-denied flight tests at speeds up to 30 m/s, the extended 2-point USAC method with algebraic refinement reduced drift rate by 36% compared with 7-point RANSAC.

### Uncertainty-Aware Optical Flow

Austin developed RAFT-U, an extension of RAFT that jointly predicts dense optical flow and calibrated per-pixel uncertainty. Incorporating this uncertainty into a factor-graph visual-inertial odometry system reduced trajectory error across infrared and electro-optical UAV flight logs. This work was accepted to IEEE/RSJ IROS 2026.

### Thermal Infrared Object Tracking

Austin's thermal infrared tracking research includes Ember, a one-stream vision-transformer tracker with a distributional bounding-box head, absence-calibrated confidence, and a memory bank for target reacquisition after occlusion.

## Publications

- [Real-Time Thermal-Inertial Odometry on Embedded Hardware for High-Speed GPS-Denied Flight](https://arxiv.org/abs/2603.02114) — arXiv preprint; submission to the *Journal of Field Robotics* pending
- *IMU-Aided Minimal Solvers and On-Manifold Essential Matrix Refinement for Robust Outlier Rejection in Thermal-Inertial Odometry* — in preparation, 2026
- *RAFT-U: Extending RAFT for Joint Optical Flow and Uncertainty Estimation* — accepted to IEEE/RSJ IROS 2026
- [Distributed Conflict Detection and Optimal 4D Trajectory Resolution Leveraging Polynomial Based Methods](https://scholarsarchive.byu.edu/studentpub/388/)
- [The BYU Mars Rover and the 2022 University Rover Challenge](https://repository.arizona.edu/handle/10150/666972)

## Experience

- Teledyne FLIR, Senior Drone Algorithm Engineer, July 2026–present
- Teledyne FLIR, Senior Algorithm Intern, January 2022–July 2026
- BYU MAGICC Lab, Undergraduate Research Assistant, November 2020–April 2022
