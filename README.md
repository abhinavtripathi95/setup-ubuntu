# Install various software and packages into your Ubuntu
A short shell script to install all the softwares and packages frequently required after a clean install of Ubuntu. The script has been written for Ubuntu 16.04LTS. These scripts were initially forked from [this repository](https://github.com/Mayankm96/setup-ubuntu.git).

## Softwares installed:
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* [vim](http://www.vim.org/download.php)
* [Robot Operating System](http://wiki.ros.org/ROS/)
* [Arduino IDE](https://www.arduino.cc/)
* [Git](https://github.com/)
* [OpenCV 3.2.0](http://opencv.org/)
* [Google Chrome](https://www.google.com/chrome/)

You will have to manually install Gazebo for ROS by going through the installation [guide](http://gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros). If you are using ROS-Kinetic, install Gazebo version:7.

## How to use?
1. Clone the repository to your system: `git clone https://github.com/abhinavtripathi95/setup-ubuntu.git`
2. On the terminal, execute the command `cd /path/to/setup_clean.sh && chmod +x *.sh`
3. After that, execute the command `./setup_clean.sh` to install all the above mentioned softwares

__NOTE:__ To install only ROS, run `./install_ROS.sh ${ROS_DISTRO}`, where `${ROS_DISTRO}=kinetic` for [Ubuntu 16.04](http://releases.ubuntu.com/16.04/)
