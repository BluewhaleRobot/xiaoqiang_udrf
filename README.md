# xiaoqiang_udrf
    xiaoqiang urdf model files
    
## input topic
    none
## output topic
      name                        type
    /joint_states        sensor_msgs/JointState
    /tf       base_link-->right_wheel base_link-->left_wheel base_link-->back_wheel
## Usage:
### download to xiaoqiang ros workspace
```
cd ~/Documents/ros/src
git clone https://github.com/BlueWhaleRobot/xiaoqiang_udrf.git 
cd ..
catkin_make
```
### Quickstart    
```
roslaunch xiaoqiang_udrf xiaoqiang_udrf.launch
```
## Made with :heart: by BlueWhale Tech corp.
    
    
    用于Rviz显示的小强3d模型文件。  
## 使用方法：
### 安装到小强ROS工作目录
```
cd ~/Documents/ros/src
git clone https://github.com/BlueWhaleRobot/xiaoqiang_udrf.git 
cd ..
catkin_make
```
### 直接启动
```
roslaunch xiaoqiang_udrf xiaoqiang_udrf.launch
```
## 由蓝鲸科技精 :heart: 制作。
