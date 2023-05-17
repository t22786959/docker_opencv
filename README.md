# Docker mnist show

## Details

[Medium Blog : https://jerin-electronics.medium.com/docker-now-ep1-python-opencv-in-docker-1dda564672c3](https://jerin-electronics.medium.com/docker-now-ep1-python-opencv-in-docker-1dda564672c3)


## Version

```bash
opencv-python==4.7.0.72
python:3.8.16
```


## Building Docker Image, running, and pushing to Dockerhub

build: 
```bash
docker build -t twist/opencv:1 .
```

run:
```bash
sh runDocker.sh
```

## Running imshow example 

```bash
python3 show.py
```


