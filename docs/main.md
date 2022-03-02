# Work plan

### Core components:

- Simulator:
  - [subt](https://github.com/osrf/subt)
  - [subt_hello_world](https://github.com/osrf/subt_hello_world)
  - [darpa-subt-challenge](https://github.com/nalindas9/darpa-subt-challenge)
- Robot - platform and contol
  - Tracked/wheeled/legged?

- LIDAR SLAM
  - [SSL_SLAM2](https://github.com/wh200720041/ssl_slam2)
    This repo is an extension work of [SSL_SLAM](https://github.com/wh200720041/SSL_SLAM). Similar to RTABMAP, SSL_SLAM2 separates the mapping module and localization module. Map saving and map optimization is enabled in the mapping unit. Map loading and localization is enabled in the localziation unit.
  - [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM)
    A-LOAM is an Advanced implementation of LOAM, which uses Eigen and Ceres Solver to simplify code structure.
  - [SC-LIO-SAM](https://github.com/gisbi-kim/SC-LIO-SAM)
    SC-LIO-SAM is a real-time lidar-inertial SLAM package.
  - [hdl_graph_slam](https://github.com/koide3/hdl_graph_slam)
    hdl_graph_slam is an open source ROS package for real-time 6DOF SLAM using a 3D LIDAR. It is based on 3D Graph SLAM with NDT scan matching-based odometry estimation and loop detection. It also supports several graph constraints, such as GPS, IMU acceleration (gravity vector), IMU orientation (magnetic sensor), and floor plane (detected in a point cloud). 
  - [LINS---LiDAR-inertial-SLAM](https://github.com/ChaoqinRobotics/LINS---LiDAR-inertial-SLAM)
    This repository contains code for a tightly-coupled lidar-inertial odometry and mapping system for ROS compatible UGVs. The reason of fusing IMU and Lidar in a tightly-couple scheme is to handle feature-less environments where previous methods may fail. 
  - [ncrl_lio](https://github.com/ChadLin9596/ncrl_lio)
    A real-time LiDAR inertial odometer system (RTLIO) is developed to achieve high-precision and high-frequency odometry and mapping for feedback control of UAVs. In contrast to the traditional LIO approach, the initialization process in this work can be performed even when the device is stationary.
  - [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM)
    This repository contains code for a lightweight and ground optimized lidar odometry and mapping (LeGO-LOAM) system for ROS compatible UGVs. The system takes in point cloud from a Velodyne VLP-16 Lidar (palced horizontally) and optional IMU data as inputs. It outputs 6D pose estimation in real-time. 
  - [LIO-SAM](https://github.com/TixiaoShan/LIO-SAM) - good
    A real-time lidar-inertial odometry package. We strongly recommend the users read this document thoroughly and test the package with the provided dataset first.
- Local planner
- Global planner

