# 华南农业大学方程式无人车迈德威视工业相机驱动包
## 步骤
#### 第一步：打开相应目录
进入 `/mvsdk_ros/src/mv-camera-ros/scripts` 目录。此文件夹中包含了我们需要用到的重要脚本。
#### 第二步：运行脚本
运行文件 `run_camera_sudo.sh`。这个脚本会启动并运行相机驱动。
### 修改分辨率
默认分辨率为640x480像素。如果需要修改,找到`MVCameraCapture.cpp`文件,并修改代码`cv::resize(bridge_.image, bridge_.image, cv::Size(640, 480));`中的像素值。

![cam](https://github.com/luojiatao/mvsdk_ros/assets/108130094/318eb644-e0fc-42dd-b32e-dcd2afa26b7a)

