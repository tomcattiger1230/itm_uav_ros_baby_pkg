# itm_uav_ros_baby_pkg

A baby package for beginner to build his own UAV package.

## Some required packages

* [PX4-Autopilot](https://github.com/PX4/PX4-Autopilot) official package for PX4 firmware for Pixhawk flight controller.
* Customized software-in-the-loop model from ITM [sitl_gazebo](https://github.com/tomcattigerkkk/PX4-SITL_gazebo). Please only copy the files that required by your simulation.
* Some special customized message definitions (including msg/srv/action) from [itm_ros_comm](https://github.com/tomcattigerkkk/itm_ros_comm).
* ACADOS should be installed following the instructions from official website [ACADOS](https://github.com/acados/acados).

## To implement

This package provides a simple implementation of MPC-based controller in ROS for a UAV working with PX4.
