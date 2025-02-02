# PX4 Container / VM support

Contains build scripts for Docker containers and virtual machines used to run Docker. Currently used for running a pre-setup ROS SITL environment, among other build setups used on CI/CD.

## Build status: [![Build Status](http://ci.px4.io:8080/buildStatus/icon?job=PX4/containers/master)](http://ci.px4.io:8080/blue/organizations/jenkins/PX4%2Fcontainers/activity)

## Base containers

### [px4io/px4-dev-base-xenial](https://hub.docker.com/r/px4io/px4-dev-base-xenial) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-xenial.svg)](http://microbadger.com/images/px4io/px4-dev-base-xenial) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-xenial.svg)](https://hub.docker.com/r/px4io/px4-dev-base-xenial)

### [px4io/px4-dev-base-bionic](https://hub.docker.com/r/px4io/px4-dev-base-bionic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-bionic.svg)](http://microbadger.com/images/px4io/px4-dev-base-bionic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-bionic.svg)](https://hub.docker.com/r/px4io/px4-dev-base-bionic)

### [px4io/px4-dev-base-archlinux](https://hub.docker.com/r/px4io/px4-dev-base-archlinux) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-base-archlinux.svg)](http://microbadger.com/images/px4io/px4-dev-base-archlinux) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-base-archlinux.svg)](https://hub.docker.com/r/px4io/px4-dev-base-archlinux)

### [px4io/px4-docs](https://hub.docker.com/r/px4io/px4-docs) [![](https://images.microbadger.com/badges/image/px4io/px4-docs.svg)](http://microbadger.com/images/px4io/px4-docs) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-docs.svg)](https://hub.docker.com/r/px4io/px4-docs)

## Composed and build specific containers

### [px4io/px4-dev-clang](https://hub.docker.com/r/px4io/px4-dev-clang) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-clang.svg)](http://microbadger.com/images/px4io/px4-dev-clang) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-clang.svg)](https://hub.docker.com/r/px4io/px4-dev-clang)

### [px4io/px4-dev-raspi](https://hub.docker.com/r/px4io/px4-dev-raspi) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-raspi.svg)](http://microbadger.com/images/px4io/px4-dev-raspi) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-raspi.svg)](https://hub.docker.com/r/px4io/px4-dev-raspi)

### [px4io/px4-dev-nuttx](https://hub.docker.com/r/px4io/px4-dev-nuttx) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-nuttx.svg)](http://microbadger.com/images/px4io/px4-dev-nuttx) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-nuttx.svg)](https://hub.docker.com/r/px4io/px4-dev-nuttx)

### [px4io/px4-dev-ecl](https://hub.docker.com/r/px4io/px4-dev-ecl) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ecl.svg)](http://microbadger.com/images/px4io/px4-dev-ecl) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ecl.svg)](https://hub.docker.com/r/px4io/px4-dev-ecl)

## Simulation containers

### [px4io/px4-dev-simulation-xenial](https://hub.docker.com/r/px4io/px4-dev-simulation-xenial) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-simulation-xenial.svg)](http://microbadger.com/images/px4io/px4-dev-simulation-xenial) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-simulation-xenial.svg)](https://hub.docker.com/r/px4io/px4-dev-simulation-xenial)

### [px4io/px4-dev-simulation-bionic](https://hub.docker.com/r/px4io/px4-dev-simulation-bionic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-simulation-bionic.svg)](http://microbadger.com/images/px4io/px4-dev-simulation-bionic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-simulation-bionic.svg)](https://hub.docker.com/r/px4io/px4-dev-simulation-bionic)

## ROS containers

### [px4io/px4-dev-ros-kinetic](https://hub.docker.com/r/px4io/px4-dev-ros-kinetic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros-kinetic.svg)](http://microbadger.com/images/px4io/px4-dev-ros-kinetic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros-kinetic.svg)](https://hub.docker.com/r/px4io/px4-dev-ros-kinetic)

### [px4io/px4-dev-ros-melodic](https://hub.docker.com/r/px4io/px4-dev-ros-melodic) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros-melodic.svg)](http://microbadger.com/images/px4io/px4-dev-ros-melodic) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros-melodic.svg)](https://hub.docker.com/r/px4io/px4-dev-ros-melodic)

## ROS2 containers

### [px4io/px4-dev-ros2-ardent](https://hub.docker.com/r/px4io/px4-dev-ros2-ardent) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-ardent.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-ardent) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-ardent.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-ardent)

### [px4io/px4-dev-ros2-bouncy](https://hub.docker.com/r/px4io/px4-dev-ros2-bouncy) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-bouncy.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-bouncy) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-bouncy.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-bouncy)

### [px4io/px4-dev-ros2-crystal](https://hub.docker.com/r/px4io/px4-dev-ros2-crystal) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-crystal.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-crystal) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-crystal.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-crystal)

### [px4io/px4-dev-ros2-dashing](https://hub.docker.com/r/px4io/px4-dev-ros2-dashing) [![](https://images.microbadger.com/badges/image/px4io/px4-dev-ros2-dashing.svg)](http://microbadger.com/images/px4io/px4-dev-ros2-dashing) [![Docker Pulls](https://img.shields.io/docker/pulls/px4io/px4-dev-ros2-dashing.svg)](https://hub.docker.com/r/px4io/px4-dev-ros2-dashing)
