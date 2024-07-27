# Usage

```bash
roslaunch robot_pose_ekf robot_pose_ekf.launch gps_sub_topic:=gps  imu_sub_topic:=imu   odom_sub_topic:=odom  vo_sub_topic:=vo
```

# Description
This package is used to fuse the data from GPS, IMU, Odom and VO to get the robot pose.

The order of fusion is `odom->imu->vo->gps`

# Reference

- [ROS Wiki] (http://wiki.ros.org/robot_pose_ekf)