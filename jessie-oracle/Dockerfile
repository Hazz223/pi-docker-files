FROM resin/rpi-raspbian:latest

RUN apt-get update

WORKDIR /java/
COPY jdk-8u121-linux-arm32-vfp-hflt.tar.gz jdk8.tar.gz
RUN tar -zxvf jdk8.tar.gz
ENV JAVA_HOME /java/jdk1.8.0_121/
# This enables java to be on the comandline
ENV PATH=$PATH:/java/jdk1.8.0_121/bin/

WORKDIR /

CMD java
