# elp_stereo_camera with point cloud for ros2

ROS2 camera driver for the ELP stereo camera, tested with ROS Jazzy and the ELP-USB3D1080P120-H120 model. Original drivers from @HeikoE

Added a file to create a point cloud. 

---

## USAGE

### Start the Camera
```bash
ros2 launch elp_stereo_camera stereo_camera_launch.py
```

### Start the point cloud
```bash
ros2 run elp_stereo_camera stereo_point_cloud_generator
```
