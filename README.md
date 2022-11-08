# docker-biohazard

A simple docker for the Biohazard bioinformatic tool.

The docker contains:
https://bitbucket.org/ustenzel/biohazard/

This image is built on Ubuntu 20.04 and the Haskell compiler.
 
 
## Build
 
I built the image by doing
 
```
docker build -t tombrazier/biohazard .
```
 
And then pushed to dockerhub
 
```
docker push tombrazier/biohazard
```

Retrieve the Docker image with

```
docker pull tombrazier/biohazard
```

## Usage
 
 
The working directory is `/mnt`.
