FROM ubuntu:jammy
WORKDIR /root
COPY sources.list sources.list
RUN mv sources.list /etc/apt/sources.list
RUN cat /etc/apt/sources.list
RUN apt update && apt install vim htop neofetch -y