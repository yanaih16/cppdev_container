FROM ubuntu:latest

RUN apt update
RUN apt upgrade -y
RUN apt install -y g++ gdb cmake git

RUN adduser docker

USER docker
WORKDIR /home/docker

RUN git clone https://github.com/atcoder/ac-library.git
ENV CPLUS_INCLUDE_PATH "/home/docker/ac-library"