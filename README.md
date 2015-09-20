# SD Robotics Club ROS Workshop

*September 22, 2015*

## Preparation

Here are the steps I did to produce the VirtualBox image that we will be using for the workshop:

1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) ([VMware](https://www.vmware.com/) would work as well)
2. Download Ubuntu 14.04.3 LTS (Trusty Tahr) 64-bit PC (AMD64) desktop image [iso (slow)](http://releases.ubuntu.com/14.04/ubuntu-14.04.3-desktop-amd64.iso) [torrent (fast)](http://releases.ubuntu.com/14.04/ubuntu-14.04.3-desktop-amd64.iso.torrent): 
3. Create new VirtualBox VM with 20GB drive (can be dynamic) - for RAM I did 4096MB.
4. Attach iso to storage of new VM (so it will boot from image)
5. Boot VM and install Ubuntu (pick default options for installation questions)
6. Reboot into Ubuntu and install VM guest additions
7. Install Xubuntu:
    $ sudo apt-get install xubuntu-desktop
8. Reboot again and [install ROS Jade](http://wiki.ros.org/jade/Installation/Ubuntu)

## Agenda

1. [Concepts](http://wiki.ros.org/ROS/Higher-Level%20Concepts)
2. [Installation](http://wiki.ros.org/jade/Installation/Ubuntu)
3. [Tutorials](http://wiki.ros.org/ROS/Tutorials)
4. [Turtlesim](http://wiki.ros.org/turtlesim), [Understanding Topics](http://wiki.ros.org/ROS/Tutorials/UnderstandingTopics)
5. [MoveIt!](http://moveit.ros.org/)
6. [Odroid C1](http://www.hardkernel.com/main/products/prdt_info.php?g_code=G141578608433)
7. ???
