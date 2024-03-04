FROM ubuntu:latest

RUN ln -snf /usr/share/zoneinfo/Etc/UTC /etc/localtime
RUN echo "Etc/UTC" > /etc/timezone
RUN apt-get update
RUN apt-get install -y texlive-full
RUN apt-get install -y git make
ENV LANG="en_US.UTF-8" 
