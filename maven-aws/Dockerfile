FROM openjdk:13-alpine

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
  jq \
  gettext \
  && pip install awscli --upgrade

ENV LOG4J_FORMAT_MSG_NO_LOOKUPS=true