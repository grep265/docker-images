# Docker Repository

This repository contains several Dockerfiles used to create Docker images with a GUI for different purposes. You can find more information in each folder.

## Windows (WSL2)

If you are running the containers from Windows using WSL2, make sure the following requirements are met:

1. Enable GUI applications in WSL2
Follow the official Microsoft guide to enable Linux GUI applications:
https://learn.microsoft.com/en-us/windows/wsl/tutorials/gui-apps

2. Enable Docker Desktop WSL integration
Ensure Docker Desktop is integrated with your WSL distribution: `Docker Desktop → Settings → Resources → WSL Integration`. Enable integration for the WSL distribution you are using.

## List of dockerfiles

* [Alpine ping](https://github.com/grep265/Docker/tree/master/alpine_ping)
* [Xclock example](https://github.com/grep265/Docker/tree/master/xclock_docker)
* [ArduPilot SITL](https://github.com/grep265/Docker/tree/master/ardupilot_sitl_docker)
* [Gazebo Garden](https://github.com/grep265/Docker/tree/master/gazebo_garden_docker)
* [Gazebo Garden & Ardupilot models](https://github.com/grep265/Docker/tree/master/gz_garden_ardupilot_docker)
* [Gazebo Harmonic](https://github.com/grep265/Docker/tree/master/gz_harmonic_docker)
* [Gazebo Harmonic & Ardupilot models](https://github.com/grep265/Docker/tree/master/gz_harmonic_ardupilot_docker)


