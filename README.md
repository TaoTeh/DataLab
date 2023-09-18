# DataLab

世界上最有价值的不是石油而是数据！
目前，数据集的数据来源主要包括相机（图片），摄像头（视频序列），激光雷达（点云），毫米波雷达，4D 成像毫米波雷达，IMU, GPS等，而相对应的任务主要包括：点云分割，目标检测与追踪等。下面将自动驾驶相关的数据集进行汇总收集并介绍。
主要介绍包括：
- 数据集下载
- 目标检测和分割数据集（图像+点云）
- 车道线检测
- 车辆运动轨迹数据集
- 交通标志(Traffic Sign)数据集
- 无人驾驶模拟器(GTA5,TORCS,CARLA,Carcraft)


# Raw Dataset
## 采集数据
- 图像数据集(Image Datasets)：包含以图像形式存储的原始数据，例如车辆摄像头获取的连续图像帧。
- 视频数据集(Video Datasets)：包含以视频形式存储的原始数据，例如车辆摄像头连续捕获的视频片段。
- 点云数据集(Point Cloud Datasets)：包含以点云形式存储的原始数据，例如由激光雷达传感器获取的数据。
- 测量数据集(Measurement Datasets)：包含来自各种传感器的测量数据，例如车辆的速度、加速度、方向等信息。

## 标注数据

## 仿真数据

# Composite Dataset
Composite Datasets Formats：
- ROS (Robotics Operating System) Bag Files > Used with Cruise Webviz
- nuScenes
- XVIZ (Uber)
- mcap (foxglove)
- Apollo 

## kitti
https://www.cvlibs.net/datasets/kitti/

## nuScenes 
https://www.nuscenes.org/

## Apollo
Apollo数据格式(Apollo Format)：Apollo是百度公司开源的自动驾驶平台，它定义了一种特定的数据格式，包含传感器数据、车辆状态信息和标注数据等。
## Udacity
Udacity数据格式(Udacity Format)：Udacity是一家在线教育公司，他们提供了一个用于自动驾驶教育的公开数据集，并定义了一种特定的数据格式，包含图像、激光雷达数据和标注信息。

## ros1 bag
https://github.com/ros/ros

## ros2 db3
https://github.com/ros2/rosbag2

## xviz
https://avs.auto/#/

## mcap
https://mcap.dev/

# 工具集
## 转换工具
- kitti -> apollo
- ros2 -> apollo
  
## 标注工具
