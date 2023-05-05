FROM ubuntu:latest

RUN apt update
RUN apt upgrade -y
RUN apt install -y g++ gdb cmake

RUN adduser docker

USER docker