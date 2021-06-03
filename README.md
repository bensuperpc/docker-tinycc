# docker-tinycc

### _tinycc compiler in docker_
 [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/powered-by-jeffs-keyboard.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/contains-cat-gifs.svg)](https://forthebadge.com)

[![docker-tinycc](https://github.com/Bensuperpc/docker-tinycc/actions/workflows/main.yml/badge.svg)](https://github.com/Bensuperpc/docker-tinycc/actions/workflows/main.yml) <img alt="Docker Image Size (latest by date)" src="https://img.shields.io/docker/image-size/bensuperpc/tinycc"> <img alt="Docker Cloud Build Status" src="https://img.shields.io/docker/cloud/build/bensuperpc/tinycc"> <img alt="MicroBadger Layers (tag)" src="https://img.shields.io/microbadger/layers/bensuperpc/tinycc/latest">

# New Features !

  - Add ARMv8 arch

#### Install
You need Linux distribution like Ubuntu or Manjaoro

```sh
git clone https://github.com/Bensuperpc/docker-tinycc.git
```
#### Build
```sh
cd docker-tinycc && make linux/amd64
```
#### Usage

```sh
./tinycc.sh tcc hello.c
```

### Todos

 - Write Tests
 - Continue dev. :D

### More info : 
- https://github.com/TinyCC/tinycc
- https://hub.docker.com/repository/docker/bensuperpc/tinycc
- https://bellard.org/tcc/
- http://www.etalabs.net/compare_libcs.html

License
----

MIT License


**Free Software forever !**
   
 
