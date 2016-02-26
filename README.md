# Introduction #
This repository contains a set of robot models in both [SDF](http://sdformat.org/) and [URDF](http://wiki.ros.org/urdf) format. It is useful for verifying that a system is compatible with both formats.

For each example robot, the SDF was generated from the URDF using the `gz` command as shown below.

    $ gz sdf -p [URDF file] > [SDF file]

`gz` is a tool that comes with [Gazebo](http://gazebosim.org/) 3.0 and above.

# How to Load Models Into Gazebo #

Add this repository to the `GAZEBO_MODEL_PATH` environment variable.

    $ cd [path to this repository]
    $ export GAZEBO_MODEL_PATH=`pwd`

Launch Gazebo:

    $ gazebo

On the left panel, switch to tab "Insert". Left-click on the robot you want to insert. The robot should appear in the Gazebo simulator.
