FROM baselibrary/java:8
MAINTAINER ShawnMa <qsma@thoughtworks.com>

## Version
ENV TOMCAT_MAJOR   7
ENV TOMCAT_VERSION 7.0.52-1

## Packages
RUN \
  apt-get update &&\
  apt-get install -y tomcat7=$TOMCAT_VERSION &&\
  rm -rf /var/lib/apt/lists/*
