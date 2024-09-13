# pcd_2_gridmap
transfrom .pcd file to ros grid map 

## run

1. set your .pcd file path in config.yaml 

2. set your parameters in map.launch (for grid map)

3. roslaunch build_octomap.launch

4. rosrun map_server map_saver (to save the grid map with topic "/map")