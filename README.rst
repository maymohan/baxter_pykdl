baxter_pykdl ROS Noetic fork
============================

This is a ROS Noetic/Python3 compatible fork of the baxter_pykdl package. ROS Noetic compatible Baxter repositories can be found here:


+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/maymohan/baxter                  |
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/maymohan/baxter_interface        |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/maymohan/baxter_tools            |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/maymohan/baxter_common           |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/maymohan/baxter_examples         |
+------------------+-----------------------------------------------------+
| baxter_simulator | https://github.com/maymohan/baxter_simulator        |
+------------------+-----------------------------------------------------+

Installation Instructions
-------------------------
System Requirements:
- OS: Ubuntu 20.04
- ROS:Noetic Ninjemys
- Python version: 3.8

These instructions assume you have followed the SDK installation procedure available on `this page <https://github.com/maymohan/baxter/wiki/Installation-Instructions>`__.

- Install dependencies
::
    
sudo apt install ros-noetic-kdl-conversions  ros-noetic-urdf-parser-plugin ros-noetic-urdfdom-py python3-lxml

- Change directory to folder with your baxter backages
::
    
cd ~/ros_ws/src/baxter

- Clone and build package
::
    
git clone https://github.com/maymohan/baxter_pykdl.git
cd ~/ros_ws/
catkin_make


Baxter PyKDL
------------

Kinamtics and dynamics scripts for the Baxter robot.

Installation
------------
| Please follow the Getting Started wiki page for instructions on installation of the Baxter SDK:
| http://sdk.rethinkrobotics.com/wiki/Workstation_Setup

Code & Tickets
--------------

+-----------------+----------------------------------------------------------------+
| Documentation   | http://sdk.rethinkrobotics.com/wiki                            |
+-----------------+----------------------------------------------------------------+
| Issues          | https://github.com/RethinkRobotics/baxter/issues               |
+-----------------+----------------------------------------------------------------+
| Contributions   | http://sdk.rethinkrobotics.com/wiki/Contributions              |
+-----------------+----------------------------------------------------------------+

Baxter Repository Overview
--------------------------

::

     .
     |
     +-- baxter_sdk/              baxter metapackage containing all baxter sdk packages
     |
     +-- baxter_sdk.rosinstall    rosinstall script containing all baxter sdk packages
     |
     +-- baxter.sh                convenient environment initialization script


Other Baxter Repositories
-------------------------
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/RethinkRobotics/baxter           |
+------------------+-----------------------------------------------------+
| baxter_interface | https://github.com/RethinkRobotics/baxter_interface |
+------------------+-----------------------------------------------------+
| baxter_tools     | https://github.com/RethinkRobotics/baxter_tools     |
+------------------+-----------------------------------------------------+
| baxter_common    | https://github.com/RethinkRobotics/baxter_common    |
+------------------+-----------------------------------------------------+
| baxter_examples  | https://github.com/RethinkRobotics/baxter_examples  |
+------------------+-----------------------------------------------------+
| baxter_simulator | https://github.com/RethinkRobotics/baxter_simulator |
+------------------+-----------------------------------------------------+

Latest Release Information
--------------------------

http://sdk.rethinkrobotics.com/wiki/Release-Changes
