# Introduction #
This repository contains a set of robot models in both [SDF](http://sdformat.org/) and [URDF](http://wiki.ros.org/urdf) format. It is useful for verifying that a system is compatible with both formats.

For each example robot, the SDF was generated from the URDF using the `gz` command as shown below.

    $ gz sdf -p [URDF file] > [SDF file]

`gz` is a tool that comes with Gazebo 3.0 and above.