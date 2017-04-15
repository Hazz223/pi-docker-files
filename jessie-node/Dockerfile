FROM resin/rpi-raspbian

RUN apt-get update && \
    apt-get -qy install wget unzip

WORKDIR /root/
RUN wget https://nodejs.org/dist/v7.9.0/node-v7.9.0-linux-armv7l.tar.gz
RUN tar -xvf node-v7.9.0-linux-armv7l.tar.gz -C /usr/local --strip-components=1

CMD ["node"]
