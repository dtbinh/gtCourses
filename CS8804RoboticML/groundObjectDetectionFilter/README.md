#groundObjectDetectionFilter

This project aims at exploiting probabilistic properties of the data collected by the robot to run estimation with bayes filter on several topologic parameters such as the occupancy and the height of the floor, and build a model of the surface.

Index:
- report.pdf: Experiment description and analysis
- floor_nav: ROS package for the robot autonomous driving.
- floor_mapping_b: ROS package implementing the ground traversability classification using a binary bayesian filter.
- floor_plane_filter: ROS package implementing the world elevation map using a Kalman filter.
