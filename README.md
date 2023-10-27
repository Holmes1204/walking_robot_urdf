# Walking Robot URDF 

### Test the walking robot urdf
You should clone this repository to one of your workspaces in the `src` directory, then run
```bash
catkin build wr_urdf_v1_5
```

Review the configuration in Rviz by using the following command:
```bash
roslaunch wr_urdf_v1_5 display.launch
```
To spawn the robot in Gazebo by running the following command:
```bash
roslaunch wr_urdf_v1_5 gazebo.launch
```

### Future work
- Implemented the NMPC and WBC control ller