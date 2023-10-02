# ecse473_f22_hxz936_roslab3

roslaunch roslab3 display.launch

Instruction:
One Launch file is included within the package. The file has two different arguments:

use_new_xacro: when true, it gives the robot new links and joints, including base_link and imu, and also enable user to see maps and sensor datas.
use_xacro: this determines whether to use xacro or urdf files from the previous package: navvis_description. It must be true if use_xacro_new is true.


Ps. This package must use with package navvis_description(and maps_glennan). All these packages should be placed under ~/catkin_ws/src
