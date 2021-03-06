# Docker Demo

Demo project for Dockerized Clojure REST API

## Installation

Clone the repo
```zsh
$ git clone git@github.com:matiisi/docker-demo.git
```

## Usage

```zsh
$ lein test # run tests

$ lein run # run locally
```

### Docker

```zsh
$ docker build -t "docker-demo:0.1.0" . # build container image with name and tag

$ docker images # list container images

$ docker run --name demodemo -it docker-demo:0.1.0 # run container image

$ docker ps -a # list all containers
```

### Cleanup

```zsh
$ docker rm demodemo # remove container

$ docker rmi docker-demo:0.1.0 # remove container image

$ docker rmi anapsix/alpine-java:8u144b01_jdk # remove base image for container
```
