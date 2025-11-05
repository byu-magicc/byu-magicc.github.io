<!--
EDITING GUIDELINES

The publications tab is a place to view all recent publications published by the lab with brief overviews of the work and links to the published paper.
This isn't intended to be an extensive showcase, just a compiled list with brief summaries.

To add an entry, create a new three pound header under the appropriate year, in reverse chronological order.
Follow the template below, adding the current year in reverse chronological order if necessary.
```
## 2025

### [Name of new paper](doi_link)

Brief summary of paper.

### [Previous new paper](previous_doi_link)
```
-->

## 2025

### [Infrared-Constellation-Aided Landing of eVTOL Aircraft](https://doi.org/10.2514/6.2025-1538)

This paper presents an active fiducial light pattern localization (AFLPL) system that uses an IR camera and a constellation of IR lights to provide accurate pose estimates for eVTOL aircraft landing without GPS. When fused with an IMU via an EKF, the system provided sub-decimeter precision at ranges below 40 m and successfully demonstrated accurate tracking of a landing trajectory.

### [Safety for Time-Varying Parameterized Sets Using Control Barrier Function Methods](https://arxiv.org/abs/2503.12003)

This paper introduces a novel method for autonomous system safety that uses *smooth* Control Barrier Functions (CBFs) to keep entire sets of states—not just single points—away from unsafe areas. The technique leverages log-sum-exp functions to create smooth overapproximations of these sets, allowing safety-preserving controls to be computed via convex optimization, which was validated in multi-agent simulations.

### [Deep Learning-Based Data Association in Infrared Camera Images for GPS-Denied Aircraft Landing](https://doi.org/10.2514/6.2025-1539)

This paper presents a PointNet++ based deep learning approach for associating 2D infrared detections with 3D light sources for aircraft landing in GPS-denied environments. This method is robust to high clutter, operates in real-time, and was shown on flight-test data to produce pose estimates that outperform traditional GPS.

### [Non-Uniform B-spline Trajectory Optimization using Control Point Representation Transformations](https://doi.org/10.23919/ACC63710.2025.11107650)

This paper uses non-uniform B-splines for UAV trajectory optimization, introducing transformations to MINVO and Bézier representations to leverage their tighter convex bounding properties. This approach yields trajectories that are significantly more time-optimal than uniform B-splines, though it comes with increased computational cost.

### [Vision-Based Collision Avoidance and Path Planning for UAVs Using Bearing and Pixel Area](https://doi.org/10.1109/ICUAS65942.2025.11007929)

This paper presents a UAV collision avoidance and path planning framework that uses only bearing and pixel area from a camera to predict object trajectories. This minimal-input system enables autonomous avoidance maneuvers with minimal ownship movement, improving safety in shared airspace.

### [Time-Synchronized B-Spline Path Planning for Multi-Agent UAV Systems with Fixed Speed Profiles](https://doi.org/10.1109/ICUAS65942.2025.11007834)

This paper proposes an offline path planning algorithm for multi-agent UAVs that must follow fixed speed profiles. By parameterizing uniform B-splines with a path variable to decouple geometry from speed, the method successfully ensures synchronized arrival times for coordinated missions, as shown in simulations.

### [Multiple Moving Object Detection and Tracking Across Complex Terrain and Skylines](https://doi.org/10.1109/IETC64455.2025.11039479)

This paper presents a practical, non-machine learning method for tracking multiple moving objects in cluttered environments using low-cost cameras. It combines classic techniques like Kalman Filters, the Hungarian algorithm, and RANSAC to deliver robust, real-time tracking, even across challenging skylines.

### [Low-SWaP GNSS-denied Navigation using LTE Signals of Opportunity](https://doi.org/10.1109/PLANS61210.2025.11028479)

This paper develops a low-SWaP, GNSS-denied navigation technique for UAVs using high-power terrestrial LTE signals. The system uses a low-cost SDR to measure differential pseudoranges, which are fused with IMU data via an EKF, achieving an 8.03 m RMSE in a flight test.

### [Continuous-Time Estimation in the Flat Output Space Using B-Splines](https://doi.org/10.1109/PLANS61210.2025.11028515)

This paper proposes a continuous-time trajectory estimation technique that operates in a system's differentially flat output space using B-splines, which naturally accounts for nonholonomic constraints. By first calibrating sensor-to-dynamics parameters, this method is shown in simulation to outperform traditional estimation on the configuration manifold.

### [Real-Time B-Spline Path Planning for Vision-Based Collision Avoidance](https://doi.org/10.1109/PLANS61210.2025.11028267)

This paper presents a real-time B-spline path planner for UAVs that uses only camera-derived bearing and pixel size for collision avoidance. This lightweight approach predicts obstacle trajectories and computes avoidance maneuvers, enabling autonomous decision-making in dynamic, shared airspaces.

### [Probabilistic Weapon Engagement Zones](https://doi.org/10.23919/ACC63710.2025.11107966)

This paper introduces linearized probabilistic weapon engagement zones (PEZ), a method for planning safe trajectories in pursuer-evasion games while accounting for uncertainty in both friendly and adversary states. This approach effectively approximates the true risk distribution, allowing for path optimization in uncertain, adversarial environments.

### [Conflict Detection, Resolution, and Control of Aircraft using 4D Polynomial Splines](https://doi.org/10.23919/ACC63710.2025.11107516)

This paper implements a distributed conflict detection and resolution algorithm for multiple quadrotors using 5th-order polynomial splines to define precise 4D (time-based) trajectories. The system, running on Raspberry Pi and Pixhawk hardware, successfully demonstrates that this flight path model can effectively separate vehicles.

### [Uncertainty-Aware Velocity Obstacle Avoidance](https://doi.org/10.1109/TAES.2025.3573987)

This paper presents the uncertainty-aware velocity obstacle algorithm to ensure safe navigation for multiple aerial vehicles by incorporating position and velocity uncertainty. The 3D avoidance algorithm uses uncertainty bounds from an EKF to create a "collision cone" of unsafe areas, which was validated in both simulation and hardware experiments.

### [Distributed Conflict Detection and Optimal Four-Dimensional Trajectory Resolution Leveraging Polynomial-Based Methods](https://doi.org/10.2514/1.D0450)

This paper presents a distributed conflict detection and resolution methodology using parametric fifth-order polynomial splines to define 4D aircraft trajectories. This representation allows for rapid conflict detection using Sturm sequencing and optimal resolution via gradient-based methods, as demonstrated in complex multi-aircraft simulations.

### [Optimization of 4D Splines for Unmanned Aerial System Trajectories Under Kinematic, Obstacle, and Time Constraints](https://doi.org/10.2514/6.2025-2230)

This paper presents an optimization method for 4D 5th-order polynomial splines to plan safe, kinematically and time-constrained UAS trajectories around obstacles. The method shows these splines are a special subset of B'ezier splines, inheriting their convex hull properties, and numerical experiments validate the approach for navigating dynamic environments.

## External Lists

Dr. Tim McLain

- [Publications](http://me.byu.edu/faculty/timmclain?sec=publications)
- [Google Scholar](https://scholar.google.com/citations?user=vXNuwuUAAAAJ)

Dr. Randy Beard

- [Publications](http://www.et.byu.edu/~beard/papers/preprints.htm)
- [Google Scholar](http://scholar.google.com/citations?user=cLSfhaoAAAAJ)

Dr. Cammy Peterson

- [Publications](https://ece.byu.edu/directory/cammy-peterson)
- [Google Scholar](https://scholar.google.com/citations?user=l78bmtoAAAAJ)

Dr. James Usevitch

- [Google Scholar](https://scholar.google.com/citations?user=JUKswVIAAAAJ)
