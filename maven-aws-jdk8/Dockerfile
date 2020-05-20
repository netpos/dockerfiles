FROM openjdk:8-alpine

ENV MAVEN_VERSION 3.5.4
ENV MAVEN_HOME /usr/lib/mvn
ENV PATH $MAVEN_HOME/bin:$PATH

RUN apk add --update --no-cache \
  python \
  python-dev \
  py-pip \
  maven \
  openssh \
  git \
  && pip install awscli --upgrade
