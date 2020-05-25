FROM gradle:jdk8

RUN apt-get update \
  && apt-get install --yes --no-install-recommends \
    python \
    python-dev \
    python-all-dev \
    python-setuptools \
    python-pip \
    python-wheel \
    libpython-dev \
    git \
  && pip install awscli --upgrade
