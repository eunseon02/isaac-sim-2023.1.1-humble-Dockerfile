# Isaac-Sim-2023.1.1-Humble-Dockerfile

Dockerfile for isaac-sim:2023.1.1 with ROS2 Humble


## Isaac Sim Docker Image
### Build from Source
```bash
cd docker/isaac-sim-humble
docker build -t isaac-sim:2023.1.1-humble .
```
### Pull Prebuilt Image
```bash
docker pull ghcr.io/eunseon02/isaac-sim:2023.1.1-humble-20.04
```

## Docker Run
```bash
xhost +local:docker
bash run_container.sh
```


## Run Isaac-Sim
```bash
cd /isaac-sim
./runapp.sh
```

### Reference 
[NVIDIA-Omniverse](https://github.com/NVIDIA-Omniverse/IsaacSim-dockerfiles)
