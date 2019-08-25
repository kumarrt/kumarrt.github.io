---
title: "Traffic Monitoring at Signalized Intersections Using UAV Flight Operations, Computer Vision and Deep Learning Techniques"
collection: talks
type: "Lightening Talk"
permalink: 
venue: "2019 AIAA INTELLIGENT SYSTEMS WORKSHOP"
date: 2019-07-29
location: "Cincinnati, Ohio, USA"

---

<div style="text-align: justify"> 
The road transportation system is a complex dynamic network. The signalized intersections are a key component in regulating the traffic flow in various directions. Efficient operations of traffic signal lights are necessary to avoid traffic congestions and queue formations. Department of Transportation (DOT) requires reliable information on traffic flow parameters such as direction and lane wise vehicle counts, saturation headway, saturation flow rate, queue service time, traffic arrival demand etc. in decision making process for traffic signal timings. Several manual and semi-autonomous methods have been used in the past for obtaining these parameters.  However, these methods require the personnel to be physically present in proximity of the traffic for manual counting and limit the operations to single intersection and single direction at any instance, increasing the total duration of these operations. The methods involving manual counting may also lead to unreliable results due to the mental fatigue of the personnel performing the calculations in proximity of the traffic. To address these limitations, we have worked towards automating traffic monitoring using Unmanned Aerial Vehicles (UAVs), computer vision and deep learning where traffic of different directions can be monitored simultaneously. The UAV flights are conducted for gathering the traffic video data. Further, we have developed an algorithm for post processing of traffic videos which uses sequence of operations including digital video stabilization, vehicles detection using Faster Region-based convolutional neural networks (Faster-RCNN), multi-object tracking, and computation of different traffic flow parameters. The video stabilization filters the external disturbances in traffic video frames. A pretrained Faster-RCNN is fine-tuned for vehicle detection from UAV video feed using transfer learning. The multi-object tracker is based on intersection over union (IOU) principle and allows tracking of multiple vehicles detected by the Faster-RCNN across consecutive video frames. This detection and tracking of vehicles allow evaluation of various traffic parameters including saturation headway and saturation flow rate as per the highway capacity manual (HCM) used by DOT for traffic engineering. The results obtained from traffic monitoring algorithm have been compared against the standard practices of DOT. This form of intelligent system opens new opportunities for obtaining reliable information for traffic parameters via integration in the existing infrastructure of DOT. 
</div> 

