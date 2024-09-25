<h1 align="center"> GaRLIO: Gravity enhanced Radar-LiDAR-Inertial Odometry </h1>
<p align="center">
<a href="https://rpm.snu.ac.kr"><strong>Chiyun Noh</strong></a>
·
<a href="https://rpm.snu.ac.kr"><strong>Wooseong Yang</strong></a>
·
<a href="https://minwoo0611.github.io/about/"><strong>Minwoo Jung</strong></a>
·
<a href="https://sangwoojung98.github.io"><strong>Sangwoo Jung</strong></a>
·
<a href="https://ayoungk.github.io/"><strong>Ayoung Kim</strong></a><sup>†</sup>
<br/>
<a href="https://rpm.snu.ac.kr/"><strong>Robust Perception and Mobile Robotics Lab (RPM)</strong></a>
</p>


**(Under Review) [IEEE ICRA 25]** This repository is the official repository for for **GaRLIO**.
[![Video Label](http://img.youtube.com/vi/zeH3RQdIviw/sddefault.jpg)](https://youtu.be/zeH3RQdIviw?si=aZg_WZfn4ErqkNu8)

## Abstract
Recently, gravity has been highlighted as a crucial constraint for state estimation to alleviate potential vertical drift. 
Existing online gravity estimation methods rely on pose estimation combined with IMU measurements, which is considered best practice when direct velocity measurements are unavailable. However, with radar sensors providing direct velocity data—a measurement not yet utilized for gravity estimation—we found a significant opportunity to improve gravity estimation accuracy substantially. GaRLIO, the proposed gravity-enhanced Radar-LiDAR-Inertial Odometry, can robustly predict gravity to reduce vertical drift while simultaneously enhancing state estimation performance using pointwise velocity measurements. Furthermore, GaRLIO ensures robustness in dynamic environments by utilizing radar to remove dynamic objects from LiDAR point clouds. Our method is validated through experiments in various environments prone to vertical drift, demonstrating superior performance compared to traditional LiDAR-Inertial Odometry methods. We make our source code publicly available to encourage further research and development.



