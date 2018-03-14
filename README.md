# iCreate
SLAM testbed based on the iCreate2

# Hardware

jetsontx2

3x Intel r200 realsense

xbox 360 wireless controller and adapter


# use


```
sudo apt-get install xboxdrv
sudo apt-get install ros-kinetic-joy

```

install rtabmap standalone librariies and ros package [using these instructions](https://github.com/introlab/rtabmap_ros#rtabmap_ros-)

install [realsense libraries](http://wiki.ros.org/librealsense) and [our ros package](https://github.com/Max-Mobility/realsense)(install the `no-tf` branch!)

install the create_autonomy package [using these instructions](https://github.com/Max-Mobility/create_autonomy)

import project `iCreate_model.webgmexm` into rosmod

use the deployment's `CommViz` to see required external nodes and their launch files

copy the relevant launch files from `RosLaunchFiles` to their respective launch folders in either `/opt/ros/kinetic/share` or the user's catkin workspace
