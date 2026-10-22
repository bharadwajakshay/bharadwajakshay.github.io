---
title: "Cost-Effective Mapping Platform to Generate HD-Maps for Autonomous Vehicles and Digital Twins"
collection: publications
category: theses
permalink: /publication/2026-06-04-phd-thesis-hd-maps
excerpt: 'Ph.D. dissertation on a cost-effective mobile mapping system for HD-map generation, covering photogrammetric camera calibration, learning-based LiDAR–camera calibration, and neural implicit LiDAR–inertial odometry.'
date: 2026-06-04
venue: 'University of Calgary, Schulich School of Engineering'
paperurl: 'https://doi.org/10.11575/PRISM/51522'
citation: 'Bharadwaj, A. S. (2026). &quot;Cost-Effective Mapping Platform to Generate HD-Maps for Autonomous Vehicles and Digital Twins.&quot; Ph.D. Dissertation, University of Calgary. doi:10.11575/PRISM/51522'
---

Scalable and cost-effective generation and updating of high-definition maps (HD-maps) remains a foundational challenge for the widespread deployment of autonomous vehicles, contingent on the accuracy of the underlying sensor calibration and localization pipelines. To enable precise mapping, a rigorous full camera system modeling approach is adopted. Checkerboard-based calibration methods, despite not being intended for mission-critical applications, have become widely used in practice. In this work, intrinsic and extrinsic camera calibration are revisited within the framework of photogrammetric self-calibration (PSC). It is demonstrated that PSC consistently outperforms checkerboard-based methods in both accuracy and precision across diverse vision tasks, including 3D reconstruction, SfM, visual SLAM, and novel view synthesis.

Accurate fusion of camera imagery with onboard sensors such as LiDAR and IMU is critical for reliable perception and mapping. While camera–inertial calibration is well studied, LiDAR–camera extrinsic calibration remains challenging, particularly outside controlled environments. To address this limitation, a two-step learning-based calibration framework is proposed. Instance-wise correspondences derived from everyday objects in the scene are first used to estimate coarse extrinsic parameters, which are subsequently refined using an end-to-end neural network to obtain fine calibration estimates. This approach enables continuous adaptation to sensor pose variations in real-world settings.

To construct and maintain geometrically consistent maps from LiDAR scans, neural implicit methods have emerged as an effective alternative to classical approaches, achieving comparable accuracy with significantly lower storage for map representation. However, their accuracy degrades in highly dynamic scenarios such as pedestrian motion. To address this, a neural implicit inertial odometry framework is introduced that jointly integrates LiDAR and inertial measurements to produce geometrically consistent 3D point clouds. Fine geometric detail is preserved through adaptive LiDAR downsampling and neural point correspondences for accurate inter-scan odometry estimation, and an attention-based loop closure mechanism ensures global consistency in large-scale mapping.

The proposed tools and algorithms are evaluated on benchmark datasets, including Oxford-Spires, KITTI, and EuRoC-MAV, and further validated on a newly collected dataset acquired using a cost-effective prototype mobile mapping system developed as part of this work, in both driving and backpack configurations.
