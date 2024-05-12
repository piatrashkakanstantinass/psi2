FROM ubuntu:latest

RUN ln -snf /usr/share/zoneinfo/Etc/UTC /etc/localtime
RUN echo "Etc/UTC" > /etc/timezone
RUN apt-get update
RUN apt-get install -y texlive-full
RUN apt-get install -y git make inkscape
ENV LANG="en_US.UTF-8" 

# Install draw.io
RUN apt-get install -y wget xvfb
RUN ARCH=$(dpkg --print-architecture) && \
  wget -P /var/drawio.deb "https://github.com/jgraph/drawio-desktop/releases/download/v24.2.5/drawio-${ARCH}-24.2.5.deb"
RUN apt-get install -y /var/drawio.deb/*.deb
