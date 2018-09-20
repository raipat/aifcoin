FROM debian:stretch
LABEL maintainer="Aif Developers <dev@aif.org>"
LABEL description="Dockerised AifCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
