# MapMyWorld

## Running the Scripts
Run the following commands below in separate terminals:<br>
Launch the world in Gazebo:<br>
```
catkin_make
source devel/setup.bash
roslaunch my_robot world.launch
```
Launch the teleop node for keyboard control:<br>
```
roslaunch my_robot keyboard_teleop.launch
```

Launch the RTAB-Map mapping node:<br>
```
roslaunch my_robot mapping.launch
```

## RTAB-Map Visualization Tools - Databse Viewer
After stop mapping.launch in terminal then we can run the following command:<br>
```
rtabmap-databaseViewer ~/rtabmap.db
```
You can download RTAB-Map from [here](https://drive.google.com/file/d/1G-35cxtPT6hSTfwrm7oBY9KZzjKG0vpz/view?usp=sharing).
