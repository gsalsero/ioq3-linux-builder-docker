FROM debian:latest
MAINTAINER gsalsero

RUN apt-get update -y && \
    apt-get install -y \
        zip \
        git \
        build-essential \
        libsdl2-dev \
        mingw-w64 \
	libxxf86dga-dev \ 
	libcurl4-openssl-dev

CMD /bin/bash
