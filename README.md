# Isaac-Sim-2023.1.1-humble-Dockerfile

Dockerfile for isaac-sim:2023.1.1 with ros2 humble


## Docker Build
```bash
cd docker/isaac-sim-humble
docker build -t isaac-sim:2023.1.1-humble .
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