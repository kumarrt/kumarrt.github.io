---
title: "Quaternion Feedback Based Full Pose Control of a Quadcopter UAV with Thrust Vectoring Capabilities"
collection: talks
type: "Presentation"
permalink: 
venue: "44th Dayton-Cincinnati Aerospace Sciences Symposium, AIAA"
date: 2019-03-05
location: "Dayton, Ohio, USA"

---

<div style="text-align: justify"> 
In  this  paper, we  present afull  pose  controller i.e.  position  and  attitude  flight  controller for a quadcopter with thrust vectoring capabilities. This UAV falls in the category of multirotors with tilt-motion enabled rotors. These UAVs utilize angular motion of propellers and tilting motion of rotors to achieve desired statein flight. Quaternion state feedback is utilized to compute the control commands for the UAV. Avoidance of gimbal lock in attitude representation and comparatively simple composition than Euler angles makes the use of quaternion space more advantageous. In this work, the conventional Euler angle transformations or direction cosine matrices are not used. The  quaternion  implementation  reduces  the  overall  complexity  of  state  estimation  as  the quaternion  differential  equations  do  not  contain  any  trigonometric  parameters.  The  quadcopter dynamic model and state space is utilized to design the attitude controller for the UAV. Lyapunov stability  analysis  of  the  system  is  shown  to  prove  stability  of  quaternion  feedback  loop.  The quaternion feedback attitude controller is complimented by an outer position controller loop which generates desired quaternions commands for the system. The performance of the UAV is evaluated by numerical simulations for tracking step and sinusoidal attitude commands and for following a predefined trajectory as part of a special maneuver in way point navigation mission.

</div> 

