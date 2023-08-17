# perception-base


Base Dockerfile for autonomous perception software (CUDA 12, Ubuntu 20.04, ROS Humble).

Github Actions CI is configured to build the Dockerfile and push to [leungjch/perception-base](https://hub.docker.com/repository/docker/leungjch/perception-) at Dockerhub.

## Build

```
docker build -t leungjch/cuda118-tensorrt-base:latest -f Dockerfile.cuda118-tensorrt-base .
```