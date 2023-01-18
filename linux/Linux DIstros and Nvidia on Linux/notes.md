# Recommended Distros for Laptops with Nvidia GPUs
Nvidia GPUs on linux have generally been a issue. Issues include driver kernel modules clashing with kernel (Using a new kernel). Many distros apart from ubuntu may ship with  open source nouveau  drivers that are not the best for newer GPUs (Post 10xx series).Installing nvidia drivers should automatically disable these drivers and use the official ones. If not so , you will need to pass kernel arguments for it. 
1. Ubuntu has decent support for nvidia GPUS and installing them are easy.Refer to the ubuntu folder on how to . Best for ROS
2. PopOS (https://pop.system76.com/) by system 76 . One of the better distros for nvidia GPUs and has switchable graphics support built in. Recommedned for ROS as it is based off Ubuntu.
3. Arch Linux .User has to install drivers.This can be a rabbit hole.Recommned research before using Arch. Too many distros. 
4. Fedora(https://getfedora.org/).One of the best distros but is rough for a beginner to learn to set it up. Nobara,based off fedora. this is recommended if going this route. 

# Cons of Nvidia on Linux 
1. No full wattage support . Some laptops have GPUS that can use upto 100+W.As of Jan 2023, they are limited to 80W.
2. Lower features as compared to windows 
3. Poor graphics switching between iGPU and dGPU.
* The following may or may not happen to everyone 
4. May break distros and cause random bugs. 
5. Display glitches 
6. Excessive battery drain due to dGPU not idling when not used.


# Distro Independent ROS 
 * Using solutions like Docker or distrobox(https://github.com/89luca89/distrobox) will work on any distro independent of host. 

# Links for thought 

https://www.reddit.com/r/linux_gaming/comments/qyldwv/i_want_to_get_into_linux_but_i_am_concerned_my/

https://www.reddit.com/r/linux/comments/wc6h7x/why_is_nvidia_hated_so_much_by_linux_users/

https://www.reddit.com/r/linux_gaming/comments/z38o78/how_bad_is_nvidia_on_linux/

# Guide to Install Drivers 

https://docs.nvidia.com/datacenter/tesla/tesla-installation-notes/index.html


## Note
AMD GPUs are better supported on linux. 
If stuff is working fine , don't mess with it. There is a higher chance of breaking stuff. 
