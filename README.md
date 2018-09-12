# docker_example
Warning: Dockerfile will copy all contents of same directory.
## Getting Started Example
1. Download docker: https://www.docker.com/products/docker-desktop
2. Open terminal or command prompt
3. Download and copy Dockerfile to its own unique directory
4. Copy what script/program you want to run in docker to the same directory as the Dockerfile
5. Build the image. The -t flag is the tag, or name of the image.__
   `docker build -t centos:centos7 .`
6. Start the container__
   `docker run centos:centos7`

## This is the most basic Dockerfile, for anything addition, please see the docker docs
https://docs.docker.com/
   
