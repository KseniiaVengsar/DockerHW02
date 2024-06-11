
FROM ubuntu:latest
COPY . /usr/src/docker1
WORKDIR /usr/src/docker1
RUN apt update
RUN apt install -y g++ nano
RUN g++ -o DockerProject main.cpp
CMD ["./DockerProject"]