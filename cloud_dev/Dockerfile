FROM debian:latest
MAINTAINER Varun Kashyap
RUN apt-get update \
  && apt-get install -y curl python zip \
  && curl --silent --show-error --retry 5 https://bootstrap.pypa.io/get-pip.py | python \
  && pip install awscli \
  && curl sdk.cloud.google.com | bash
