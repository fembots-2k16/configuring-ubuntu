# configuring-ubuntu
for running ros and our project and stuff

## todo
	1. move piberry configuration/dependency stuff to that git

---------------------------------------------
## alternatively just use my chromebook (username: mercury password: ubuntuubuntu)

1. http://wiki.ros.org/indigo/Installation/Ubuntu

2. creating a catkin_ws
 
    $ mkdir -p ~/catkin_ws/src

    $ cd ~/catkin_ws/src
    
    $ catkin_init_workspace


    $ cd ~/catkin_ws/
    
    $ sudo apt-get install build-essential
    
    $ catkin_make
    
    $ source devel/setup.bash
    
3. installing necessary ros packages (and p2os)
 
    $ cd ~/catkin_ws/src

    $ git clone https://github.com/allenh1/p2os
    
    $ sudo apt-get install ros-indigo-tf ros-indigo-diagnostics ros-indigo-urdf ros-indigo-robot-model
    
    $ catkin_make

4. get piberry launch stuff: https://github.com/fembots-2k16/piberry-launch
    
5. set up homework5: https://github.com/fembots-2k16/homework5
