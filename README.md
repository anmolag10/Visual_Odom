# Visual Odometery using Rtabmap
## How to run
1. Install
   ```bash
         sudo apt-get install ros-melodic-rtabmap-ros
 
      ```
2. Check the required transform between base_link and camera_link exists, edit the launch file, or publish the following transform
    ``` bash
           rosrun tf static_transform_publisher 0 0 0 0 0 0 1 camera_link base_link 10
           ```
 3. Launch the launch file for respective rgb or stero odometry 
    
  
