---
title: "A Navigation and Mapping Method for UAS during Under-the-Canopy Forest Operations"
collection: publications
category: conferences
permalink: /publication/2016-09-25-forest-navigation
excerpt: 'A simultaneous navigation and mapping (SNAM) method for multi-copter UAS operating in GNSS-degraded forest environments, using tightly-coupled GNSS/IMU and multi-scanner ICP-based mapping.'
date: 2016-04-11
venue: '2016 IEEE/ION Position, Location and Navigation Symposium (PLANS)'
paperurl: '/files/A_navigation_and_mapping_method_for_UAS_during_under-the-canopy_forest_operations.pdf'
citation: 'Schultz, A., Gilabert, R., Bharadwaj, A., Uijt de Haag, M., &amp; Zhu, Z. (2016). &quot;A Navigation and Mapping Method for UAS during Under-the-Canopy Forest Operations.&quot; <i>2016 IEEE/ION Position, Location and Navigation Symposium (PLANS)</i>. Savannah, GA. pp. 739-746. doi:10.1109/PLANS.2016.7479768'
---

This paper presents the preliminary design and implementation of a Simultaneous Navigation and Mapping (SNAM) method for multi-copter UAS operating under forest canopy where GNSS signals are unreliable. A 3DR hexacopter platform was equipped with multiple 2D laser scanners, cameras, GNSS, and an IMU running on ROS. The hierarchical GNC framework uses a tightly-coupled GNSS/INS estimator when satellites are available, and falls back on ICP-based scan matching with IMU aiding in degraded conditions. Dual laser scanners (forward and downward-slanted) provide terrain-referenced altitude estimation and 3D tree mapping. Flight tests in a temperate Ohio forest demonstrated successful 3D position/attitude estimation and 2D tree map generation under challenging multipath and foliage conditions.
