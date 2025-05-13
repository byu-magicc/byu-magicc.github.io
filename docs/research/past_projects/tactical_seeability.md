# Tactical Seeability

Unmanned Air Systems (UASs) are used to strategically position aerial sensors, such Electro-Optical or Infra-Red cameras, to perform surveillance, tracking, and other missions. The position of the UAS, the ground location where the sensor is pointing, the resolution of the sensor, and other parameters all affect the quality of the received sensor measurements. This research has two main topics: To study and model the quality of sensor video, and to use this model to autonomously plan a UAS flight path and sensor schedule that maximizes the UAS operators' ability to detect and identify objects of interest from the video stream.

## Video Utility Metric

In the literature, there exists methods to estimate an operator's abiliity to perform detection, recognition, and identification (DRI) tasks when observing an image. The targeting task performance (TTP) metric developed by Volmerhaussen and Jacobs is the state of the art method to estimate the probability of an operator sucessfully performing DRI tasks. Unfortunately, there is no previously existing method to estimate the probability of an operator successfully performing DRI tasks when observing video. For this reason, we extend the TTP metric by developing the video TTP (VTTP) metric.

When observing images, object size, resolution, and contrast with the background are significant factors in determining whether or not an operator wil find the desired object. These factors are all considered when calculating the TTP value. When observing video, at least two additional components are needed. Blur due to motion and where the object is located in the video frame both affect the probability of an operator detecting the object. The VTTP metric is calculating the TTP value of a hypothetical object at a terrain point within the video, and then scaling the TTP value based on the amount of motion.

## Project Members

Dr. Randy Beard, Dr. Bryan Morse, Dr. Stephen Pledgie, Peter Niedfeldt, Brandon Carroll, and Joel Howard

## Project Timeline

Phase 1: December 2008 - July 2009

Phase 2: August 2009 - October 2011

## Publications

P. Niedfeldt, B. T. Carroll, R. W. Beard, J. Howard, B. Morse, and S. Pledgie. "Enhanced UAS Surveillance Using a Video Utility Metric". Under Review for International Journal on Unmanned Systems (World Scientific).

P. Niedfeldt, B. T. Carroll, R. W. Beard, and S. Pledgie. "A Staged Path Planner for an Unmanned Air System Performing Surveillance. AIAA 2012-4786, Proceedings of the 2012 AIAA Guidance, Navigation, and Control Conference, San Francisco, CA, USA.

P. Niedfeldt, R. W. Beard, and S. Pledgie. "Integrated Sensor Guidance Using Probability of Object Identification". Proceedings of the 2010 American Control Conference, Baltimore, MD, USA. pp. 788-793.
