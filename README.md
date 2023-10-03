# 华南农业大学方程式无人车迈德威视工业相机（MV-LD-4-4M-G）驱动包
## 步骤
#### 第一步：打开相应目录
进入 `/mvsdk_ros/src/mv-camera-ros/scripts` 目录。此文件夹中包含了我们需要用到的重要脚本。
#### 第二步：运行脚本
运行文件 `run_camera_sudo.sh`。这个脚本会启动并运行相机驱动。
## 注意：修改像素值需要修改MVCameraCapture.cpp文件中的    cv::resize(bridge_.image, bridge_.image, cv::Size(640, 480));代码，修改后需要重新编译。
