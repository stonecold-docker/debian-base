# debian-base
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/debian-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/debian-base)



----------------------------------------
### x64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/debian-base/latest)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/debian-base/latest)
### aarch64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/debian-base/aarch64)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/debian-base/aarch64)
### x64_stable
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/debian-base-stable/x64stable)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/debian-base-stable/x64stable)



----------------------------------------
#### Description

* Distribution : [Debian GNU/Linux](https://www.debian.org/)
* Architecture : x64,aarch64
* Appplication : -



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           forumi0721/debian-base:[ARCH_TAG]
```



----------------------------------------
#### Usage

```dockerfile
FROM forumi0721/debian-base:[ARCH_TAG]

#For cross compile on dockerhub (aarch64)
RUN ["docker-build-start"]

RUN 'build-code'

#For cross compile on dockerhub  (aarch64)
RUN ["docker-build-end"]
```



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |

