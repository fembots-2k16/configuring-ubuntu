# configuring-ubuntu
for running ros and our project and stuff

## WHEN IN DOUBT: source ~/catkin_ws/devel/setup.bash

---------------------------------------------
## alternatively just use my chromebook (username: mercury password: ubuntuubuntu)

1. http://wiki.ros.org/indigo/Installation/Ubuntu

2. creating a catkin_ws and installing dependencies
 
    $ mkdir -p ~/catkin_ws/src

    $ cd ~/catkin_ws/src
    
    $ catkin_init_workspace
    
    $ git clone https://github.com/allenh1/p2os


    $ cd ~/catkin_ws/
    
    $ sudo apt-get install build-essential ros-indigo-tf ros-indigo-diagnostics ros-indigo-urdf ros-indigo-robot-model
    
    $ catkin_make
    
    $ source devel/setup.bash

4. get piberry launch stuff: https://github.com/fembots-2k16/piberry-launch
    
5. set up homework5: https://github.com/fembots-2k16/homework5
