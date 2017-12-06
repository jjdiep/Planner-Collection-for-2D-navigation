# 16-782-Planning-Project

The code is an implementation of [planner ensemble](https://www.ri.cmu.edu/pub_files/2014/5/The_Planner%20Ensemble_and_Trajectory_Executive_small.pdf) for a simple 2D navigation for differential drive robot. 

In this code we have 3 planners.
1) [CHOMP](https://www.ri.cmu.edu/pub_files/2009/5/icra09-chomp.pdf)
2) [ADA\*](http://www.cs.cmu.edu/~ggordon/likhachev-etal.anytime-dstar.pdf)
3) [RRT\*](http://www.roboticsproceedings.org/rss06/p34.pdf)

# Implementation
All planners are implemented in C++ and the visualizations are in MATLAB. The ADA\* implementation is a modified version of the one found in [SBPL](https://github.com/sbpl/sbpl).

# Requirements
## CHOMP
1) [Armadillo-8.300.1](http://arma.sourceforge.net/download.html).
2) [LAPACK-3.8](http://www.netlib.org/lapack/#_lapack_version_3_8_0_2)

## ADA*
1) SBPL, provided in the repository.

## RRT*
1) Self contained

# Compiling the planners
