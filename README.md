# cluster_detector
# Branch: logistics


# v0.0
+ ground plane filter
+ object cluster
+ bounding box maker


# v1.0 20211126
+ \+ boundary maker



# v1.1 20211201
+ \+ delete some unnecessory boundary points   361 points -> near 240 points


# Dependencies:
+ Ubuntu 16.04 or 18.04
+ ROS version correspond to Ubuntu 16.04 or 18.04
+ PCL (automate installed with ROS)

# use

+ cd $CLUSTER_ROOT/src/cluster_detector/
+ change the topic name and parameters in cluster_detector.launch according to the LiDAR type and position

+ cd $CLUSTER_ROOT
+ catkin_make
+ source devel/setup.bash
+ roslaunch cluster_detector cluster_detector.launch