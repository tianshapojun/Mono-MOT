# Mono-MOT
This repo is built upon https://github.com/aleksandrkim61/EagerMOT. Thanks for their excellent work!

# Modified items
### Version 0.0
* 添加后处理模块，支持 a.根据轨迹文件，将相机坐标系转为世界坐标系；b.对同一物体缺失帧进行补全；
### Version 0.1
* 优化后处理模块，支持 a.由于轨迹误差+感知误差+追踪误差，出现物体抖动，实现动/静物体判断，静止物体固定坐标，动态物体优化轨迹；
### Version 0.2
* 优化后处理模块，支持 a.多物体类别追踪，目标为车(Car)、人(Pedestrian)、障碍物(Cone)；
