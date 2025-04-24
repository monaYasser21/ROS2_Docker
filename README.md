I pulled an `ubuntu:24.04` image, as ROS 2 only works on this version or higher.

You can download these files and place them in a directory, along with a copy  
from your `.bashrc` file. Don't forget to source it:

```bash
source /opt/ros/jazzy/setup.bash

PS: I ran it as root, but you can run it either as root or by adding a user, like ros_jazzy
