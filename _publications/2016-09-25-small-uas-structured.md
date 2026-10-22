---
title: "Small-UAS Navigation using 3D Imager and Infrared Camera in Structured Environments"
collection: publications
category: conferences
permalink: /publication/2016-09-25-small-uas-structured
excerpt: 'A GNSS-denied navigation and thermal mapping method integrating depth imagery from a 3D TOF imager and LWIR camera with an IMU for autonomous small-UAS operation in maintenance tunnels.'
date: 2016-04-11
venue: '2016 IEEE/ION Position, Location and Navigation Symposium (PLANS)'
paperurl: '/files/Small-UAS_navigation_using_3D_imager_and_infrared_camera_in_structured_environments.pdf'
citation: 'Bharadwaj, A., Schultz, A., Gilabert, R., Huff, J., &amp; Uijt de Haag, M. (2016). &quot;Small-UAS Navigation using 3D Imager and Infrared Camera in Structured Environments.&quot; <i>2016 IEEE/ION Position, Location and Navigation Symposium (PLANS)</i>. Savannah, GA. pp. 599-606. doi:10.1109/PLANS.2016.7479751'
---

This paper introduces a positioning and navigation algorithm for autonomous small-UAS flight in GNSS-denied structured environments (maintenance tunnels). A Blackout quadcopter was equipped with an Occipital 3D depth camera (structured-light TOF), a Lepton LWIR thermal camera, and a Pixhawk IMU, all interfaced through ROS on an Odroid XU4 onboard computer. The navigation method integrates 3D point cloud features with IMU data for 6-DOF pose estimation. Planar surface features are extracted via RANSAC and environment slicing; edge and point features are extracted from the depth image. The LWIR sensor simultaneously creates a thermal anomaly map for detecting steam leaks, hot pipes, and insulation failures. Flight tests in Ohio University maintenance tunnels demonstrated successful real-time feature extraction at 3 Hz on the embedded processor.
