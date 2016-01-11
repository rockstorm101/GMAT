# GMAT - General Mission Analysis Tool

The General Mission Analysis Tool (GMAT) is the world’s only enterprise, multi-mission, open source software system for space mission design, optimization, and navigation. The system supports missions in flight regimes ranging from low Earth orbit to lunar, libration point, and deep space missions. GMAT is developed by a team of NASA, private industry, public, and private contributors and is used for real-world mission support, engineering studies, as a tool for education, and public engagement.

[GMAT Web Site](gmatcentral.org)

## Motivation

The build and install process of GMAT on Mac/Linux is both tedious and unclear, this repository aims to ease and detail this process so Mac/Linux users can "effortlessly" enjoy this software.

Therefore this is an **unofficial** repository of GMAT R2015a. It simply gathers all the necessary files from the [official repository](http://sourceforge.net/projects/gmat/), adds a compile-and-install script and details the installation process.

This work is inspired in the work done by @natronics in [this repository](https://github.com/natronics/GMAT). However, this previous work has now become outdated thus this newer repository being necessary.

## Installation and Run

### Dependencies

The following dependencies are needed to build and run GMAT on Mac/Linux:

 * build-essential
 * cmake
 * csh
 * curl
 * dos2unix
 * freeglut3-dev
 * g++
 * libdevil-dev
 * libgl1-mesa-dev
 * libglu1-mesa-dev
 * libgtk2.0-dev
 * libgtk-3-dev

You can manually install them or try running `LinuxInstallDependencies` as administrator.

### Build and Install

To build and install GMAT simply clone this repository

`git clone ...`

and run the compile-and-install script

`cd GMAT`
`./LinuxCompileAndInstall`

A folder will be created ("GMAT-R2015a" by default) with all the necessary files to run GMAT.

### Run GMAT

To run GMAT simply execute the file `<installation_directory>/bin/GMAT`.

## Usage

The `application/docs` folder contains some documentation. The [official site](gmatcentral.org) contains both end-user and developer documentation, tutorials and training material.

## License

Apache License v2.0. See `License.txt`

## Support

For bugs, feature requests, comments or advise please fill in an issue.

