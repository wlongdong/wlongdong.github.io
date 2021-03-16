---
title: "Autonomous Driving for Tracked Robot in Off-road Environment"
excerpt: "In an off-road environment, the assumption of horizontal ground is usually invalid, so IMU and wheel encoder are integrated to rectify LiDAR motion distortion and estimate ego-motion. In addition, [LPD-Net](https://github.com/qiaozhijian/LPD-Net-Pytorch.git) (reproduced by myself) is integrated into [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM.git) to detect loop closure, which builds a more accurate map for map-based localization. Finally, a loosely-coupled method based on the pose graph is constructed to provide the robot with robust and accurate pose.
 <br/>
<img src='/images/localize.gif' width='500'>"
collection: portfolio
---

In an off-road environment, the assumption of horizontal ground is usually invalid, so IMU and wheel encoder are integrated to rectify LiDAR motion distortion and estimate ego-motion. In addition, [LPD-Net](https://github.com/qiaozhijian/LPD-Net-Pytorch.git) (reproduced by myself) is integrated into [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM.git) to detect loop closure, which builds a more accurate map for map-based localization. Finally, a loosely-coupled method based on the pose graph is constructed to provide the robot with robust and accurate pose.
 <br/>
<img src='/images/robot.jpg' width='300'>

### Demo
<img src='/images/localize.gif' width='500'>
