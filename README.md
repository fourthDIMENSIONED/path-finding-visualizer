
![](figures/cover0.png)
# Pathfinding Visualizer

## Overview

A tool for visualizing numerous pathfinding algorithms. The project extensively uses SFML and C++.

![](figures/cover1.png)

## Dependencies

* cmake >= 2.8
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* SFML >= 2.5.1
  * All OSes: [click here for installation instructions](https://www.sfml-dev.org/tutorials/2.5/#getting-started)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level project directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./main`.

### SFML Installation on Linux

There are different approaches to the installation of SFML on Linux. For example, on Debian you would do:

`sudo apt-get install libsfml-dev`

>Please note that the minimum version of SFML required in this project is 2.5.1. and at the time of writing you can only install sfml-v2.5.1 directly from debain distribution's package repository for Ubuntu 20.04, otherwise please install it from source.

- Follow this [thread](https://en.sfml-dev.org/forums/index.php?topic=20638.0) to build SFML from source on Ubuntu versions less than 20.04.
