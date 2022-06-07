# Snort
Dockerized version of snort version 3 (https://www.snort.org/snort3). Pre-build image can be found here: https://hub.docker.com/r/hsrnetwork/snort3

## Prerequisites
None

## Build the Image
```bash
docker build -t hsrnetwork/snort:lastest .
```

## Getting Started
```bash
docker run -it hsrnetwork/snort:latest
```
or
```bash
docker-compose up -d
```