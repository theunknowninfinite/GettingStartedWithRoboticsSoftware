# ROS on windows 
The latest version of WSL has GUI support , allowing for ROS to run with gui app support.
1. Install WSG-G - https://github.com/theunknowninfinite/GettingStartedWithRoboticsSoftware
2. Install ROS as you would on ubuntu 
Pros is that you don't need additional software or VM machines. 

# Potential Downfalls of WSLg
1. Might be a bit laggy compared to directly running it on a linux host.
2. Gazebo acts buggy and may need debugging.
3. Consumes a bit more resources compared to running on bare  metal.
4. Might not work for industrial projects, have not experimented with host USB and network access 
5. Docker might be better 

# ROS on Arch Linux 
1. Add the repo : https://github.com/arch4edu/arch4edu/wiki/Add-arch4edu-to-your-Archlinux
2. Install  the apt version of ROS , in this example, ROS noetic, using paru. ````paru -S ros-noetic-desktop````
3. Use ROS as normal 

# Notes:
 
* Would recommend ubuntu as using on other platforms may reult in debugging a lot compared to using it on ubuntu.
* Have not done tried connecting to devices using ROS. 
* Debian will work as well as ubuntu will.(Ubuntu is based off Debian)