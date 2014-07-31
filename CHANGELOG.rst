^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package moveit_visual_tools
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.1.0 (2014-07-31)
------------------
* Bug fixes
* Fixed convertPoint32ToPose
* Added scale to publishText
* New publishPolygon, publishMarker, convertPose, convertPointToPose, and convertPoint32 functions
* New deleteAllMarkers, publishPath, publishSpheres, and convertPoseToPoint functions
* Added getCollisionWall
* Made lines darker
* Added reset marker feature
* Namespaces for publishSphere
* New publishTrajectory function
* Merging features from OMPL viewer
* Refactored functions, new robot_model intialization
* Added more rand functions and made them static
* Added graph_msgs generated messages dependence so it waits for it to be compiled
* Updated README
* Contributors: Dave Coleman, Sammy Pfeiffer

1.0.1 (2014-05-30)
------------------
* Updated README
* Indigo support
* Fix for strict cppcheck and g++ warnings/errors
* Compatibilty fix for Eigen package in ROS Indigo
* Fix uninitialized
* Fix functions with no return statement and other cppcheck errors
* Contributors: Bence Magyar, Dave Coleman, Jordi Pages

1.0.0 (2014-05-05)
------------------
* Enabled dual arm manipulation 
* Removed notions of a global planning group, ee group name, or ee parent link. 
* Changed functionality of loadEEMarker
* Added new print function
* Made getPlanningSceneMonitor() private function
* Renamed loadPathPub()
* Added tool for visualizing unmangled stack trace
* Created function for publishing non-animated grasps
* Created new publishGraph function. Renamed publishCollisionTree to publishCollisionGraph
* Created functions for loading publishers with a delay
* Removed old method of removing all collision objects
* Created better testing functionality
* Changed return type from void to bool for many functions
* Changed way trajectory is timed
* Created new publishIKSolutions() function for grasp poses, etc
* Added new MoveIt robot state functionality
* Added visualize grasp functionality
* Removed unnecessary run dependencies
* Updated README

0.2.0 (2014-04-11)
------------------
* Improved header comments are re-ordered functions into groups
* Started to create new trajectory point publisher
* Added getBaseLink function
* Added dependency on graph_msgs
* Added new collision cylinder functionality
* Created example code in README
* Renamed visualization to visual keyword
* Updated README

0.1.0 (2014-04-04)
------------------
* Split moveit_visual_tools from its original usage within block_grasp_generator package
