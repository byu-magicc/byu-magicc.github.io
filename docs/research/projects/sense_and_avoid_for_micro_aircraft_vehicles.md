# Sense and Avoid for Micro Aircraft Vehicles

Collision avoidance becomes a problem when an unmanned micro aircraft vehicle is sharing the same airspace as a manned aircraft. Utilizing radar on the vehicle can help give the unmanned aircraft bearing and range of the observed vehicle, but radars are heavy and expensive. Meanwhile, cameras are cheap and inexpensive, but they lack in a range measurement. The purpose of this project is to utilize cheap and lightweight cameras to plan safe paths around observed vehicles.

This project has a few areas a research, the first being target tracking using computer vision, the second being collision avoidance path planning, and the third being range estimation with bearing and pixel measurements.

## Sponsors

This project is funded by Utopia Compression Corporation

- [Utopia Compression Corporation](https://utopiacompression.com/)

## Personnel

### Students

- [Curtis Evans](../../directory/students/curtis_evans.md)
- Jen Jui Liu

### Faculty

- [Dr. Randy Beard](../../directory/faculty.md)

## Significant Results

- Tracking an anaconda drone while the camera is in a stationary location. The outputs of this tracking algorithm are essentially the bounding box which contains a bearing in the x and y direction and a pixel size, i.e. how big is the bounding box. These outputs are what is used in the path planning and range estimation.
![type:video](https://www.youtube.com/embed/UrTG5mWmrlE)


- Real-time path planning in a 2D scenario using only bearing and pixel measurements. The video shows ownship avoiding the wedges, which is a collision free path. The wedge is an area of where the observed object is likely to be, so a successful avoidance of the wedge is a succesful avoidance of the observed object.
![type:video](https://www.youtube.com/embed/Y97FsTZLnfo)

## Papers, Theses, and Presentations

- [Real-Time B-Spline Path Planning for Vision-Based Collision Avoidance](https://ieeexplore.ieee.org/abstract/document/11028267)
- [Multiple Moving Object Detection and Tracking Across Complex Terrain and Skylines](https://ieeexplore.ieee.org/abstract/document/11039479)
- [Vision-Based Collision Avoidance and Path Planning for UAVs Using Bearing and Pixel Area](https://ieeexplore.ieee.org/abstract/document/11007929)

